LAUREN BARER 
SFSU-ID: 918330561
                        CSC 665 PROJECT 2
                
QUESTION #1 Reflex Agent:

EXPLANATION AND AUTOGRADER OUTPUT

- For question 1 I made sure that pacman was getting the closest food distance and making sure
  he stays away from the ghost. I used the manhatten distance and that was my evaluation function. 

(csc665) macbook-pro:multiagent labarer$ python autograder.py -q q1
Starting on 10-12 at 14:32:27

Question q1
===========

Pacman emerges victorious! Score: 1228
Pacman emerges victorious! Score: 1209
Pacman emerges victorious! Score: 1209
Pacman emerges victorious! Score: 1215
Pacman emerges victorious! Score: 1228
Pacman emerges victorious! Score: 1231
Pacman emerges victorious! Score: 1231
Pacman emerges victorious! Score: 1224
Pacman emerges victorious! Score: 1227
Pacman emerges victorious! Score: 1231
Average Score: 1223.3
Scores:        1228.0, 1209.0, 1209.0, 1215.0, 1228.0, 1231.0, 1231.0, 1224.0, 1227.0, 1231.0
Win Rate:      10/10 (1.00)
Record:        Win, Win, Win, Win, Win, Win, Win, Win, Win, Win
*** PASS: test_cases/q1/grade-agent.test (4 of 4 points)
***     1223.3 average score (2 of 2 points)
***         Grading scheme:
***          < 500:  0 points
***         >= 500:  1 points
***         >= 1000:  2 points
***     10 games not timed out (0 of 0 points)
***         Grading scheme:
***          < 10:  fail
***         >= 10:  0 points
***     10 wins (2 of 2 points)
***         Grading scheme:
***          < 1:  fail
***         >= 1:  0 points
***         >= 5:  1 points
***         >= 10:  2 points

### Question q1: 4/4 ###


Finished at 14:37:20

Provisional grades
==================
Question q1: 4/4
------------------
Total: 4/4



QUESTION #2 Minimax:

EXPLANATION AND AUTOGRADER OUTPUT

- For question 2 minimax I used the psuedocode and algorithm to make sure it finds 
  the best node path and works using the minimax tree

(csc665) macbook-pro:proj1-search-python3 labarer$ python autograder.py -q q2
Starting on 9-23 at 21:05:59

Pacman died! Score: 84
Average Score: 84.0
Scores:        84.0
Win Rate:      0/1 (0.00)
Record:        Loss
*** Finished running MinimaxAgent on smallClassic after 36 seconds.
*** Won 0 out of 1 games. Average score: 84.000000 ***
*** PASS: test_cases/q2/8-pacman-game.test

### Question q2: 5/5 ###


Finished at 14:38:33

Provisional grades
==================
Question q2: 5/5
------------------
Total: 5/5



QUESTION #4 Expectimax:

EXPLANATION AND AUTOGRADER OUTPUT

- Question four I used my minimax fuction but changed it so it was expectimax, 
  also adding an average function to it

Pacman died! Score: 84
Average Score: 84.0
Scores:        84.0
Win Rate:      0/1 (0.00)
Record:        Loss
*** Finished running ExpectimaxAgent on smallClassic after 36 seconds.
*** Won 0 out of 1 games. Average score: 84.000000 ***
*** PASS: test_cases/q4/7-pacman-game.test

### Question q4: 5/5 ###


Finished at 14:40:56

Provisional grades
==================
Question q4: 5/5
------------------
Total: 5/5



QUESTION #5 Better Evaluation Function

EXPLANATION AND AUTOGRADER OUTPUT

- Question 5 was pretty easy I used my old evaluation fucntion just modified it 
  slightly and got it working 

Pacman emerges victorious! Score: 1170
Average Score: 1018.3
Scores:        976.0, 949.0, 973.0, 1172.0, 964.0, 978.0, 950.0, 871.0, 1180.0, 1170.0
Win Rate:      10/10 (1.00)
Record:        Win, Win, Win, Win, Win, Win, Win, Win, Win, Win
*** PASS: test_cases/q5/grade-agent.test (6 of 6 points)
***     1018.3 average score (2 of 2 points)
***         Grading scheme:
***          < 500:  0 points
***         >= 500:  1 points
***         >= 1000:  2 points
***     10 games not timed out (1 of 1 points)
***         Grading scheme:
***          < 0:  fail
***         >= 0:  0 points
***         >= 10:  1 points
***     10 wins (3 of 3 points)
***         Grading scheme:
***          < 1:  fail
***         >= 1:  1 points
***         >= 5:  2 points
***         >= 10:  3 points

### Question q5: 6/6 ###


Finished at 14:46:01

Provisional grades
==================
Question q5: 6/6
------------------
Total: 6/6



