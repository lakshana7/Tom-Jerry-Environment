<h1>RL Environment Description</h1>
</br>
<p>The “TomJerryEnvironment” is a grid-world depiction of a scene that was inspired by 
vintage Tom and Jerry cartoons. The design of the grid is 6 by 6 and had several different 
elements, such as cheese, ice cream, Jerry, Tom, and traps. Jerry's main objective is to make 
his way through the grid, dodging Tom's traps, gathering ice cream for reinforcement, and 
eventually getting to the cheese for a significant reward. Jerry, the agent, has the capacity to 
move in four directions: up, down, right, and left. Jerry's position, state-specific rewards, 
and the general health of the grid are all monitored by the environment.  
Agent: In this environment, jerry is our agent to collect maximum rewards during its 
learning phase. 
</br>
<b>States:</b> On the grid, Jerry, ice cream cones, cheese, traps, and Tom remain in for the states.  
{S1 = (0, 0) -> jerry position, S2 = (0, 1) -> icecream, S3 = (0, 2), S4 = (0, 3) -> icecream, 
S5 = (0, 4), S6 = (0, 5) -> trap, S7 = (1, 0) -> trap, S8 = (1, 1), S9 = (1, 2)->trap,  
S10 = (1, 3) -> trap, S11 = (1, 4) -> icecream, S12 = (1, 5), S13 = (2, 0)-> Trap,  
S14 = (2, 1) -> icecream, S15 = (2, 2) -> icecream, S16 = (2, 3)-> Tom, S17 = (2, 4),  
S18 = (2, 5) -> trap, S19 = (3, 0) -> icecream, S20 = (3, 1) -> Trap, S21 = (3, 2) -> 
icecream, S22 = (3, 3)->trap, S23 = (3, 4)-> Cheese, S24 = (3, 5) -> Trap, S25 = (4, 0), S26 = (4, 1),  
S27 = (4, 2) -> trap, S28 = (4, 3), S29 = (4, 4) -> Trap, S30 = (4, 5), S31 = (5, 0), S32 = 
(5, 1) -> Trap, S33 = (5, 2), S34 = (5, 3) -> icecream, S35 = (5, 4), S36 = (5, 5) -> icecream} 
</br>
<b>Actions: </b>Jerry encounters four different actions: moving up, down, right, and left.  
</br>
<b>Goal: </b>Jerry loves cheese so our agent’s goal is to collect cheese at the end of the game. 
</br>
<b>Rewards:</b> Reward distribution is decided by Jerry's position in the environment. Ice cream 
provides a reward of +3, rat traps incur a -1 penalty. If Jerry gets to the cheese, it’s the goal 
so +10 reward, but if it gets caught by tom then the environment resets and he gets punished -5.  
</br>
<b>Objective: </b>Jerry's main objective is to make his way via the grid, overcome obstacles across 
the way, and get to the cheese to get maximum rewards.</p>

