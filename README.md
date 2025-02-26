Download link :https://programming.engineering/product/homework-7-electronic/

# Homework-7-Electronic
Homework 7 Electronic
Question 1: D-Separation

You are given several graphical models below, and each graphical model is associated with an independence

(or conditional independence) assertion. Please specify if the assertion is true or false.

Please write your answer for each subpart in one row.

1) Assertion: It is guaranteed that I is independent of G given H; E; C

2) Assertion: It is guaranteed that A is independent of I given B; D

VE 492 : Electronic #7 (Due July 8th, at 11:59pm)

3) Assertion: It is guaranteed that K is independent of H given A; L

4) Assertion: It is guaranteed that L is independent of K given A; C; J

5) Assertion: It is guaranteed that F is independent of H given A; I

VE 492 : Electronic #7 (Due July 8th, at 11:59pm)

6) Assertion: It is guaranteed that C is independent of L given K.

VE 492 : Electronic #7 (Due July 8th, at 11:59pm)

Question 2: Variable Elimination

Consider the graphical model shown below, where all variables have binary domains. We are given the

query P (F j + c). Assume that we run variable elimination with the following ordering: B; D; E; A.

After introducing evidence, we have the following factors:

P (A); P (B); P (+c j A; B); P (D j +c); P (E j +c; D); P (F j A; +c; B; E)

Step 1: After joining on B and summing out over B, we have generated a new factor f1 over the following variables and/or evidence (note B is not included after summing out over B):

A

B

+c

D

E

F

x

x

x

x

After this step, the remaining factors are:

P(A)

P(B)

P(+cjA,B)

P(Dj+c)

P(Ej+c,D)

P(FjA,+c,B,E)

f1

x

x

x

x

Step 2: After joining on D and summing out over D, we have generated a new factor f2 over the following variables and/or evidence (note D is not included after summing out over D):

Sample answer:

AB + cDEF

After this step, the remaining factors are:

Sample answer:

P(A)P(B)P(+c j A; B)P(D j +c)P(E j +c; D)P(F j A; +c; B; E)f1f2

VE 492 : Electronic #7 (Due July 8th, at 11:59pm)

Step 3: After joining on E and summing out over E, we have generated a new factor f3 over the following variables and/or evidence (note E is not included after summing out over E):

Sample answer:

AB + cDEF

After this step, the remaining factors are:

Sample answer:

P(A)P(B)P(+c j A; B)P(D j +c)P(E j +c; D)P(F j A; +c; B; E)f1f2f3

Step 4: After joining on A and summing out over A, we have generated a new factor f4 over the following variables and/or evidence (note A is not included after summing out over A):

Sample answer:

AB + cDEF

After this step, the remaining factors are:

Sample answer:

P(A)P(B)P(+c j A; B)P(D j +c)P(E j +c; D)P(F j A; +c; B; E)f1f2f3f4

Reminder: The nal factor (or the product of nal factors if there are more than one) is guaranteed to be equal to selected joint P (F; +c). To answer the original query, we need to renormalize to obtain P (F j +c).

