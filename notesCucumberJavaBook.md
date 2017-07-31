#Notes on Cucumber+Java book

> Unit tests - build the thing right
> Acceptance tests - build the right thing

Investigate: Cucumber's Wire protocol; QTP?

```
Given - context;
When - event(s);
Then - outcome(s);
```

When writing scenarios - each scenario must make sense and be able to be executed independently of any other scenario. When running a scenario always assume it'll be running against a system in default blank state; You then tell the story and set up the state you need in scenarios by using Given steps in each particular scenario.

> Take good care when naming scenarios;

On the step definition you can put a ? after a character to specify you don't care if that character shows up or not in the steps;

non capturing groups:   (?:visit|go to) - this won't be captured, and steps can have one of the two.

If the background is more than 4 lines long - find a way to express it in less lines;
Avoid technical details like: "clearing queues", starting backend services; opening browsers in backend; there are ways to push these actions to support code;

A DataTable can be read as an argument in a cucumber step;

in feature file:
```
    "step being defined:"
        |Oranges |  <-- data table
        |Apples  |
        |Potatoes|

    Then the argument on stepdef must be DataTable; - This is a List<List<String>>
```

There are methods useful in the DataTable - .diff(), .get(row), .set(column, value)

> Using Data Tables is different than using tables in Scenario Outlines;
