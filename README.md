# Assignment-2-CSC-370-solution

Download Here: [Assignment 2 CSC 370 solution](https://jarviscodinghub.com/assignment/assignment-2-csc-370-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1 (20 marks)
Provide an E/R diagram for a database storing information involving teams, players and their
fans. Some additional information you must include in your design:
• For each team – its name, its players, its team captain (who is one of its players), and the
colours of its uniform.
• For each player – their name.
1
• For each fan – their name, favorite teams, favorite players, and favorite colour.
Here note that a set of colours is not a suitable attribute type for teams. You must find a way
around this restriction.
Question 2 (20 marks)
Below is an E/R diagram for a credit union named “The Trust-Us Trust”. The diagram is for a
database involving clients and accounts. Clients may have more than one account, and those
accounts may be held jointly by more than one client. Therefore each client is associated with
an account set, and accounts are members of one or more account sets. Assuming the meaning
of the various relationships and attributes are as normally expected by their names, provide a
thorough critique of the design. What design rules appear to be violated in the diagram? Why?
How would you modify the design?
AcctSets Clients
Accounts Addresses
Member of
Has
Lives at
owner-address name
balance
number
address
E/R diagram for Question 2
Question 3 (20 marks)
Referring to your E/R diagram prepared in question 1:
• Select and specify keys.
• Indicate appropriate referential integrity constraints
2
You must motivate and explain your choices.
Question 4 (30 marks)
We may think of relationships in the E/R model as having keys, just as entity sets do. Let R
be a relationship among the entity sets E1,E2,…,En. Then a key for R is a set K of attributes
chosen from the attributes of E1,E2,…,En such that if (e1,e2,…,en) and (f1, f2,…, fn) are two
different tuples in the relationship set for R, then it is not possible that these tuples agree in all
the attributes of K. Now, suppose n = 2: that is, R is a binary relationship. Also, for each i, let
Ki be a set of attributes that is a key for the entity set Ei
. In terms of E1 and E2, give the smallest
possible key for R under the assumption that:
(a) R is many-to-many.
(b) R is many-to-one from E1 to E2.
(c) R is many-to-one from E2 to E1.
(d) R is one-to-one.
Question 5 (25 marks)
Consider the following situation that involves weak entity sets. There exist entity sets named
Courses and Departments. A course is given by a unique department, but its only attribute is its
number. Different departments can offer courses with the same number. Each department has
a different name. Draw the E/R diagram that models all of this.
Question 6 (25 marks)
Consider the E/R diagram shown in the assignment writeup for this question (refer to page 4).
Convert the design into a relational schema.
Question 7 (30 marks)
Consider the E/R diagram shown in the assignment writeup for this question (refer to page 5).
Convert the design into a relational schemas using, in turn, each of the following:
(a) The straight E/R method.
(b) The object-oriented method.
(c) The nulls method.
3
toCust toFit
Bookings
Customers Flights
row
SIN
name
addr
phone number
day
aircraft
seats
E/R diagram for Question 6
Question 8 (30 marks)
Recall the database-design problem from Question 1. For the question, please convert your
design into the Object Definition Language. Make sure you include the keys as you deem them
appropriate. The original question introduced a complication involving team colours. Explain
why this is not an issue for ODL, and do so by providing a small example.
4
FatherOf Married
MotherOf
ChildOf
Child Father
Person
Mother
name address
E/R diagram for Question 7

