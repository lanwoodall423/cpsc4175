# Allen Woodall
## Software Engineering
## Homework 6
---
1. C# and Python - 
Problem Domain 1 - Creating a game. I would choose C# for the simple reason of the Unity editor supporting C# natively. A game would take drastically more time to develop outside of Unity so Java would not work well. 
Problem Domain 2 - Creating an automated plant watering system. Using a Raspberry Pi and Python this could be achieved easily. An alternative would be using an Arduino and the Arduino language which is similar to C/C++ but would be more cumbersome as it isn't the same as C#.
Problem Domain 3 - A customer needs a high performance solution. - C# would be a better means of implementing a performance dependent piece of software though Cython allows for C extensions to improve Python performance.
Problem Domain 4 - A customer needs a cross-platform softare. - Python programs can natively run on OSX, Linux, and Windows. Full .NET is Windows only though Linux has limited capabilities for it.
2. A variable for storing a count called "theCountVariable." Just call it "count." Also don't call the count "asdasda" as that is not meaningful. Instead of a set of variables like "maxSpd," "minimumSpeed," and "curS" use "maxSpeed," "minSpeed," and "currentSpeed" so that the relation is clear and understood.  
3.  The only "standard" I see might be the "DRY" principle which is that if you use a scrippet of code twice, make a sub-procedure for it instead of continuing to recode the same thing repeatedly.
4. In creating a game for Games 1 I found myself calling for elements of an array repeatedly. Instead of continuing to write code over and over to find a particular element I just made a method that finds the element based on an attribute it has. 
5. A stub is a piece of code used to stand in for some other functionality. It may simulate the behavior of existing code (such as a procedure on a remote machine) or be a substitute for yet-to-be-developed code. A driver is a temporary piece of code for testing a code artifact. It fills a similar role to the stub.
6. Top Down Integration: Strengths: Major design flaws show up early. Due to the order in which things are implemented, top-down has error isolation which saves time fixing issues. Weakness:  Potentially reusable code artifacts may not be adequately tested.
7. Bottom-up integration: Strengths:  Operational artifacts are tested thoroughly.  Testing is done with the aid of drivers, rather than by fault-shielding,
defensively programmed artifacts. Weakness: Major design faults
are detected late in the implementation workflow.
used
8. A particular language may be better to implement one part of the system, perhaps the bottom-up part. Another language may be better for the other portion so through a DSL you can link the two parts together.
9. The implementation group is assuring the implementation doesn't have faults and the SQA group is assuring that all software requirements are properly met. 
10. I can appreciate a call for more static, sequential programming. It is certainly more intuitively understandable which is something to at least strive for even if not universally achievable. What I take from this piece is an urge for caution and not an expression of goto statements being lethal. The letter primarily made me think of the need to attempt to keep things as simple and efficient as possible and somewhat reminded me of the need for decoupling.  
