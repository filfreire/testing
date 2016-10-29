Triage team is composed by:
- QA
- Lead Developer
- Product Owner

Bugs are not good or bad: they are important or not.
Priority(importance of the bug) and severity (amount of damage).

A minor bug in a part of the project deemed critical by stakeholders may have hight priority but low severity; Priority of bugs change with the business and technical context; Those that decide bug priority and severity should be acutely aware of business context. Who are the stakeholders? Who are the customers?

Look out for bugs with high severity!

One lonely bug might not be bad - a swarm of them can aggravate users and render project unusable. Low severity bugs with easy workaround can generate many support calls too.

In some software, a gramatical error can have no effects, but in software related to important areas like medical software, a grammatical error can have devastating effects (ex. how a patient's medical history is read).

Poor software engineering practices - swamp of bugs ensured.

Fixing bugs is a business decision - sometimes there is little or no benefit to be gained by fixing a bug.

Some bugs are not apparent from the start.

Test plan - it's like a net to catch bugs - depends on time and budget for testing. Sometimes it is better to explore more risks, than to explore some risks in depth.

FAST tests- Functional Acceptance Simple tests - tests every capability with normal data to gain confidence that the system handles normal inputs - but doesn't guarantee the system handles invalid inputs properly.

Have a Test plan to catch big bugs, then a finner test plan, if you have the time, to catch smaller bugs.
If a bug won't be fixed, users can by encouraged to use the software in a way that avoids the bug.

Self-veryfied data checks - the software can be checked against a testing oracle - good to find data integrity bugs.

Different techniques should be used to find different kinds of bugs - buffer overflow technique is not the same as calculation techniques; data integrity is not the same as user interface /business logic techniques;

Tricks to stop bugs comming into the programs:
- Configuration management;
- Requirements Management;
- Test Management;
These are a must have - so bugs are caused by the project risks and not poor project management.

Development discipline, static analysis, inspections, peer reviews on new code; unit testing; good development practices; good architecture;

QUOTE: "Salespeople from tool vendors sometimes misrepresent the costs and benefits of tools and their ease of use. For example, they may claim that a test automation tool that can capture actions and play them back will "solve all your problems". They'll say, "Take this tool, and you can write a program that will find all your bugs." This sounds attractive at first, but these types of tools require a very large amount of programming and don't really solve any problems. They also make maintaining tests a nightmare. Tool vendors may also claim that a requirements tracking tool "will reduce costs". But the tool itself will not save money; what will save money is having the discipline to manage requirements."

Don't rely on only one technique or tool!

When fixing the bug - are other quality factors compromised? Like performance, reliability, availability, maintainability.

Don't get stuck at solving the wrong problem: Best thing to do sometimes is to step back from the project and look at the big picture. Take time to understande requirements, indentify helpful technologies, tools, skills and processes. Otherwise you can get stuck at solving the wrong problem!

Bug bash - before release of the product - expose as many bugs as you can before release; Random testing techniques (*Investigate this*).

Unit test - use assertions to test whether a program is in the state it should be during execution.

Frogs like bugs - we should like to find bugs!
*Idea: what if we gamified finding bugs, to make the idea even more likable?*

A frog belly can hold a limited number of bugs.
A development team doesn't have the time, effort and money to fix all the bugs found - so bug priority is established based on cost/benefit analysis.

Bugs can camouflage: either in plain sight; or by being cancelled out by another bug; or a big bug can hide a small bug.

"Be sneaky": Some bugs are best caught by system monitoring (*search BoundsChecker*); (example: inappropriate access to system resources and memory leakages) or others, like browser compatibility bugs, when you test software as normal while varying the browser;

Always look at:
- How we found the bug;
- Whether or we have to fix it right away;
- How much damage can it cause.

If we use the program in a different way, we can avoid some bugs. Sometimes a workaround is better, if there is no time for regression testing.

Quick patches don't solve problems - fix it the first time.


Some bugs are dealbreakers for some people, but for other people, they're not.

If we decide to fix a bug - double check the fix always! - Regression testing is important!

How do we know we're finished?
Some think "it's when I go home", and then catapult the code to the next phase, which results in poor quality.
To answer the question use: requirements management, configuration management and testing.
Ensure some things first like:
- Code Coverage;
- Static analysis;
- Usability;
- Reliability;
- Maintainability.

"Exit criteria" - make sure everyone on the project understands their role in the completion of tasks, and exit criteria are accurately defined in their minds.

Our job is done when the bugs left are the ones we can live with.


