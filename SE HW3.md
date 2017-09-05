# Allen Woodall
## 8/27/17 Homework 3 ##
1. A software requirements specification must contain functional and/or non-functional requirements. It also contains constraints such as a due date or portability to specified hardware/operating systems.

2. “The software must print a report only when sales fail to reach their
target.” 
The intention here could be to print monthly reports only if sales don't reach their monthly target to avoid reporting when it's unnecessary. However, it could be interpreted as the software needs to be able to print reports **only** when the sales target isn't reached. Perhaps management wants a report even though sales were above the target one month. If this requirement was interpreted incorrectly that wouldn't be possible. Requirements need to be specific and concise and their creator needs to be vigilant.

3. The professors' chosen system of grading is represented in the middle. The student submits work, and receives graded work back. The professor applies grades and feedback to the work within the grading system.

4.  The cart begins empty. When an item is added to the cart it changes to a state that reflects that it's in use,"user is shopping." This could be "collecting" or anything that denotes in-progress shopping. Items can be added, keeping it in the shopping state. All items can be removed, returning it to empty. When shopping is complete the cart goes to checkout where items are paid for and removed. Perhaps checkout could connect back to empty cart.

5.  Customers, Orders, and Products each need a unique ID as their primary keys. One customer can have zero to many orders and orders can have one to many products. Each class have various additional attributes like Name for Product or Email for Customer.

6.  I made an SADT of a player's turn in my group's Battleship game. The player enters the coordinates they desire to attack. The board which is a 2d array is the data brought in. The output is a response as to whether the attack hit or missed. Based on my reading in the book and elsewhere online I'm thinking I need to see the presentation for SADT tomorrow. I feel like I don't have a complete grasp of it.

7.  

8.  This function has the schema name "OverFill" and was in a slideshow I found that explained the basics of Z notation. The symbol that looks like "[n]" but with horizontal instead of vertical braces is called Xi and indicates that the operation doesn't change the values of state variables. Amount is an input("?") and is defined as a positive integer, "N." "r" is   an output("!") of type CHAR. The first predicate tells us that capacity is always less than "contents" plus the inputted "amount." The last predicate defines the output "r!" as "Insufficient tank capacity - Fill canceled."  
