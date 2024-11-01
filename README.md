[1] Russell and Norvig 
[2] AIMA-Data 

1 For the 4×3 world shown in Figure 17.1 (a). Calculate which squares can be reached from (1,1) by the action sequence [Right,Right,Up,Up,Right] and with what probabilities. 
1.1 Do this under two scenarios—one deterministic and one stochastic. 
1.2 Use Figure 17.1 (b) to define the nature of the movement, but the probability of left is 0.0, of forward is 1.0, and of right 0.0. 
1.3 Repeat the analysis, but the probability of left is 0.3, of forward is 0.6, and of right 0.1.

2 Write code that calculates the answers for problem 1. Compare your hand calculated answers from 1 with your program.

3 This is a programming problem. Find the optimal policies for Figure 17.2 using r = -0.02, -0.04, -0.06, and -2.00. 
3.1 Do your answers match 17.2 (b)? 
3.2 Compare the Value-Iteration (Figure 17.6) and Policy-Iteration (Figure 17.9) approaches. 
3.3 How long does it take to compute the optimal policy for each? Do they yield the same policies? 
3.4 For the Value-Iteration approach, vary the input epsilon. When does the value of epsilon change the policy?
