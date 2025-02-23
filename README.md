# 4320-6320-Operating-Systems-Homework-4
4320/6320 Operating Systems Homework 4

**Download Link:https://programming.engineering/product/4320-6320-operating-systems-homework-4/**

Description
5/5 – (2 votes)
Your programs – if requested – must compile with gcc and execute on snowball.cs.gsu.edu!

Please see https://cscit.cs.gsu.edu/sp/guide/snowball for more details. You may use whatever

IDEs / text editors you like, but you must submit your responses on iCollege.

(10 Points) Provide a deadlock-prone pseudocode for two processes each accessing two semaphores A and B.

(20 Points) Prove the correctness or give a counterexample for each of the following statements. You must state whether the statement is true or false and then show your arguments. (“->” means “implies”).

Cycle -> Deadlock

Knot -> Deadlock

(20 Points) Consider the following maximum-claim reusable resource system with four processes (P0, P1, P2, P3) and three resource types (R0, R1, R2). The maximum claim matrix C is given by

P0

R0

R1

R2

4

1

4

P1

3

1

4

P2

5

6

13

P3

1

1

6

where Cij denote maximum claim of process i for resource j. The total number of units of each resource type is given by the vector

R0

R1

R2

5

8

15

The current allocation of resources is given by the matrix A

P0

R0

R1

R2

0

1

4

P1

2

0

1

P2

1

2

1

P3

1

0

3

where Ai,j denotes the units of resources of type j currently allocated to process i. For the state shown above, determine if a new request by process P1 for 1 unit of resource R1 can be safely granted. (Remark: You can assume that the system state above does not yet consider this request.)
