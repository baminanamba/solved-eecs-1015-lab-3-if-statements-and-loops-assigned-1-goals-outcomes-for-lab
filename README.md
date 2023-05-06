Download Link: https://assignmentchef.com/product/solved-eecs-1015-lab-3-if-statements-and-loops-assigned-1-goals-outcomes-for-lab
<br>
<h1>2. LAB 3 – TASK</h1>

<h1>1 [Ticket Price]</h1>

: This task is to compute the ticket price for a person based on their age and their status as a student.

The user should input two piece of information:

<ul>

 <li>Their age as an integer</li>

 <li>If they are a student or not, either “Y” or “N”</li>

</ul>

You need to compute the type of ticket and amount they need to pay.  The possible outcomes are:

Type ‘CHILD’,  Price 0.50  – if their age is less than or equal to 12. Type ‘STUDENT’,  Price 1.00 –  if they answer “Y” to the student question Type ‘SENIOR’, Price 0.50 – if their age is greater than or equal to 65. Type ‘ADULT’, Price 1.50 – if none of the thing above are true.

Note, you should compute the lowest fare based on the input.  For example, a person who is a ‘CHILD’ or ‘SENIOR’ but is also a ‘STUDENT’ should only pay 0.50 and not the students rate of 1.00.

<h1>See output for several examples (user input is in red)</h1>

—TASK 1: Determine Fare—

What is your age?: 5

Are you a student (Y/N)?: Y

Fare Type ‘CHILD’ – Price: $0.50

—TASK 1: Determine Fare—

What is your age?: 30

Are you a student (Y/N)?: Y

Fare Type ‘STUDENT’ – Price: $1.00

—TASK 1: Determine Fare—

What is your age?: 66

Are you a student (Y/N)?: N

Fare Type ‘SENIOR’ – Price: $0.50

—TASK 1: Determine Fare—

What is your age?: 21

Are you a student (Y/N)?: N

Fare Type ‘ADULT’ – Price: $1.50

<em>Your output should look like that shown here.   Also see accompanying video. </em>

Example video for the lab: <a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>3</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>.mp4</strong></a>

<h1>2 [Print each item in string and reverse the string.]</h1>

: The user should input string.    You will print out each character one by one.  You will also print out the string in reverse order.

<h1>See output for several examples (user input is in red)</h1>

— Task 2: Print String Characters and Reverse —

Input a string: This is a test.

str[0] = ‘T’ str[1] = ‘h’ str[2] = ‘i’ str[3] = ‘s’ str[4] = ‘ ‘ str[5] = ‘i’ str[6] = ‘s’ str[7] = ‘ ‘ str[8] = ‘a’ str[9] = ‘ ‘ str[10] = ‘t’ str[11] = ‘e’ str[12] = ‘s’ str[13] = ‘t’ str[14] = ‘.’

Reversed: ‘.tset a si sihT’

— Task 2: Print String Characters and Reverse — Input a string: EECS1015 Lab3 str[0] = ‘E’ str[1] = ‘E’ str[2] = ‘C’ str[3] = ‘S’ str[4] = ‘1’ str[5] = ‘0’ str[6] = ‘1’ str[7] = ‘5’ str[8] = ‘ ‘ str[9] = ‘L’ str[10] = ‘a’ str[11] = ‘b’ str[12] = ‘3’

Reversed: ‘3baL 5101SCEE’

<em>Your output should look like that shown here.   Also see accompanying video. </em>

Example video for the lab: <a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>3</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>.mp4</strong></a>

<h1>3 [Finding the maximum value in a list of inputs</h1>

: The goal is to find the maximum value from a sequence of positive numbers.  You should ask the user to input a sequence of positive numbers (it is OK if they repeat numbers).  The end of the sequence is determined when the user enters a negative number.   You should print out the maximum number from the sequence.

<strong>See output for several examples (</strong><strong>user input is in red</strong><strong>) </strong>

— Task 3: The Maximum —-

Keep entering positive numbers.

To quit, input enter a negative number.

Enter a number: 10

Enter a number: 15

Enter a number: 11 Enter a number: 0

Enter a number: 88

Enter a number: 15

Enter a number: 33 Enter a number: 8

Enter a number: -1

Largest number entered   88

— Task 3: The Maximum —-

Keep entering positive numbers.

To quit, input enter a negative number.

Enter a number: 1039

Enter a number: 2029

Enter a number: 3333

Enter a number: 40

Enter a number: 109

Enter a number: 5555

Enter a number: -1

Largest number entered   5555

<em>Your output should look like that shown here.   Also see accompanying video. </em>

Example video for the lab: <a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>3</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>.mp4</strong></a>




Task 4: String triangle

<strong>Goal</strong>: Input a string.  Based on the inputted string, print out a triangle as shown below.  Note that case where string only is a single character (last example).

<strong>See output for several examples (</strong><strong>user input is in red</strong><strong>) </strong>

— Task 4: String triangle —

Type in a string: EECS1015

E

EE

EEC

EECS

EECS1

EECS10

EECS101

EECS1015

EECS101

EECS10

EECS1

EECS

EEC

EE

E

— Task 4: String triangle —

Type in a string: ******

*

**

***

****

*****

******

*****

****

***

**

*

— Task 4: String triangle —

Type in a string: ^^

^

^^

^

— Task 4: String triangle —

Type in a string: X

X

Example video for the lab: <a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>3</strong></a><a href="https://www.eecs.yorku.ca/~mbrown/EECS1015_Lab3.mp4"><strong>.mp4</strong></a>

<h1>3. GRADING SCHEME</h1>

This lab is more challenging than lab 2.   However, the notes and trinkets examples are all sufficient to help you do this lab.  To get full marks you need to make sure you follow the instructions correctly.   The following will be our grading scheme for the Lab components specified in Section 2 of this document.

<h1>Task 0: File name <strong>must</strong> be “py” (all lowercase, no spaces)</h1>

<ul>

 <li>The Python comments at the beginning of your program <strong>must</strong> include your name, email, and York student id (this is important for grading)</li>

 <li><em>If your file name is incorrect, your or do not put in the required information we will deduct -5 points (Why are we so harsh? Because if you don’t put in your name and student id it can be very difficult for the TAs to determine whose submission this is.)</em></li>

</ul>

<h1>Task 1-4:</h1>

<ul>

 <li>Each task should prompt the user correctly and compute the required output correctly.</li>

</ul>


