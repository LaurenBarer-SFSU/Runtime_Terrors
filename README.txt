LAUREN BARER 
SFSU-ID: 918330561

Partner: Abou Chahine - 918143608 - We worked together on this project
                       
                       CSC 665 PROJECT 3
                
QUESTION #1 Reflex Value Iteration:

EXPLANATION AND AUTOGRADER OUTPUT

- For question 1 I considered the iteration equation and wrote the iteration agent which computes the best action for the value function and returns the q value which holds the state and action.


(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q1
Starting on 11-2 at 17:46:10

Question q1
===========

*** PASS: test_cases/q1/1-tinygrid.test
*** PASS: test_cases/q1/2-tinygrid-noisy.test
*** PASS: test_cases/q1/3-bridge.test
*** PASS: test_cases/q1/4-discountgrid.test

### Question q1: 4/4 ###


Finished at 17:46:11

Provisional grades
==================
Question q1: 4/4
------------------
Total: 4/4


QUESTION #2 Bridge Crossing Analysis:

EXPLANATION AND AUTOGRADER OUTPUT

- For question 2 I filled out the analysis file with the proper perameters answer 
discount and answer noise

(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q2
Starting on 11-2 at 17:50:59

Question q2
===========

*** PASS: test_cases/q2/1-bridge-grid.test

### Question q2: 1/1 ###


Finished at 17:50:59

Provisional grades
==================
Question q2: 1/1
------------------
Total: 1/1



QUESTION #3 Policies:

EXPLANATION AND AUTOGRADER OUTPUT

- Question 3 I filled out the rest of the Analysis file to match the perameter with
the optimal policy. 

(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q3
Starting on 11-2 at 17:52:39

Question q3
===========

*** PASS: test_cases/q3/1-question-3.1.test
*** PASS: test_cases/q3/2-question-3.2.test
*** PASS: test_cases/q3/3-question-3.3.test
*** PASS: test_cases/q3/4-question-3.4.test
*** PASS: test_cases/q3/5-question-3.5.test

### Question q3: 5/5 ###


Finished at 17:52:39

Provisional grades
==================
Question q3: 5/5
------------------
Total: 5/5



QUESTION #6 Q-Learning

EXPLANATION AND AUTOGRADER OUTPUT

- Question 6 I wrote a qval agent which doesnt do much but instead learns using
the trial and error. 

(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q6
Starting on 11-2 at 17:55:43

Question q6
===========

*** PASS: test_cases/q6/1-tinygrid.test
*** PASS: test_cases/q6/2-tinygrid-noisy.test
*** PASS: test_cases/q6/3-bridge.test
*** PASS: test_cases/q6/4-discountgrid.test

### Question q6: 4/4 ###


Finished at 17:55:43

Provisional grades
==================
Question q6: 4/4
------------------
Total: 4/4


QUESTION #7 Epsilon Greedy

EXPLANATION AND AUTOGRADER OUTPUT

- Question 7 I completed the q learning by implementing the epsilon greedy by making
it choose random action an epsilon fraction of the time

(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q7
Starting on 11-2 at 18:00:55

Question q7
===========

*** PASS: test_cases/q7/1-tinygrid.test
*** PASS: test_cases/q7/2-tinygrid-noisy.test
*** PASS: test_cases/q7/3-bridge.test
*** PASS: test_cases/q7/4-discountgrid.test

### Question q7: 2/2 ###


Finished at 18:00:56

Provisional grades
==================
Question q7: 2/2
------------------
Total: 2/2


QUESTION #8 Bridge Crossing Revisited

EXPLANATION AND AUTOGRADER OUTPUT

- Question 8 I went back to the analysis file and filled it out to return
the corect parameters. 

(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q8
Starting on 11-2 at 18:07:42

Question q8
===========

*** PASS: test_cases/q8/grade-agent.test

### Question q8: 1/1 ###


Finished at 18:07:42

Provisional grades
==================
Question q8: 1/1
------------------
Total: 1/1


QUESTION #9 Q-Learning and Pacman

EXPLANATION AND AUTOGRADER OUTPUT

- Question 9 was similar to the other q learning question, used similar syntax

### Question q9: 1/1 ###


Finished at 18:10:46

Provisional grades
==================
Question q9: 1/1
------------


QUESTION #10 Approximate Q-Learning

EXPLANATION AND AUTOGRADER OUTPUT

- Question 10 I implementd the approximate q learning which takes information on the 
weights and features of the states. 

(csc665) macbook-pro:reinforcement labarer$ python autograder.py -q q10
Starting on 11-2 at 18:25:42

Question q10
============

*** PASS: test_cases/q10/1-tinygrid.test
*** PASS: test_cases/q10/2-tinygrid-noisy.test
*** PASS: test_cases/q10/3-bridge.test
*** PASS: test_cases/q10/4-discountgrid.test
*** PASS: test_cases/q10/5-coord-extractor.test

### Question q10: 3/3 ###


Finished at 18:25:43

Provisional grades
==================
Question q10: 3/3
------------------
Total: 3/3




