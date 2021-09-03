LAUREN BARER 
SFSU-ID: 918330561
                        CSC 665 PROJECT 0
                
QUESTION #1 ADDITION:

EXPLANATION AND AUTOGRADER OUTPUT

- For question 1 it was straight forward and simple. We were suposed to pass in value a and b and add them up. 
  Get the sum. Bellow is the autograder output. 

(csc665) macbook-pro:tutorial labarer$ python autograder.py -q q1
Starting on 9-2 at 20:03:18

Question q1
===========

Passed a=1 and b=1, returning a+b=2
*** PASS: test_cases/q1/addition1.test
*** 	add(a,b) returns the sum of a and b
Passed a=2 and b=3, returning a+b=5
*** PASS: test_cases/q1/addition2.test
*** 	add(a,b) returns the sum of a and b
Passed a=10 and b=-2.1, returning a+b=7.9
*** PASS: test_cases/q1/addition3.test
*** 	add(a,b) returns the sum of a and b

### Question q1: 1/1 ###


Finished at 20:03:18

Provisional grades
==================
Question q1: 1/1
------------------
Total: 1/1

Your grades are NOT yet registered.  To register your grades, make sure
to follow your instructor's guidelines to receive credit on your project.



QUESTION #2 BUYLOTSOFFRUITS FUNCTION:

EXPLANATION AND AUTOGRADER OUTPUT

- Question 2 was prety straight forward and simple too. The goal was to add a function which would take a list
of the fruit by the pound and return the cost. Which is what the code does and returns total costs. Bellow is 
the autograder 

(csc665) macbook-pro:tutorial labarer$ python autograder.py -q q2
Starting on 9-2 at 20:07:56

Question q2
===========

*** PASS: test_cases/q2/food_price1.test
*** 	buyLotsOfFruit correctly computes the cost of the order
*** PASS: test_cases/q2/food_price2.test
*** 	buyLotsOfFruit correctly computes the cost of the order
*** PASS: test_cases/q2/food_price3.test
*** 	buyLotsOfFruit correctly computes the cost of the order

### Question q2: 1/1 ###


Finished at 20:07:56

Provisional grades
==================
Question q2: 1/1
------------------
Total: 1/1

Your grades are NOT yet registered.  To register your grades, make sure
to follow your instructor's guidelines to receive credit on your project.




QUESTION #3 SHOPSMART FUNCTION:

EXPLANATION AND AUTOGRADER OUTPUT

- With this code i had a bit of an issue. I kept getting an error because I forgot to call getCostPerPound, 
when I called it the code started working perfectly. Bellow is the autograder for q3.

(csc665) macbook-pro:tutorial labarer$ python autograder.py -q q3
Starting on 9-2 at 20:13:25

Question q3
===========

Welcome to shop1 fruit shop
Welcome to shop2 fruit shop
*** PASS: test_cases/q3/select_shop1.test
*** 	shopSmart(order, shops) selects the cheapest shop
Welcome to shop1 fruit shop
Welcome to shop2 fruit shop
*** PASS: test_cases/q3/select_shop2.test
*** 	shopSmart(order, shops) selects the cheapest shop
Welcome to shop1 fruit shop
Welcome to shop2 fruit shop
Welcome to shop3 fruit shop
*** PASS: test_cases/q3/select_shop3.test
*** 	shopSmart(order, shops) selects the cheapest shop

### Question q3: 1/1 ###


Finished at 20:13:25

Provisional grades
==================
Question q3: 1/1
------------------
Total: 1/1

Your grades are NOT yet registered.  To register your grades, make sure
to follow your instructor's guidelines to receive credit on your project.
