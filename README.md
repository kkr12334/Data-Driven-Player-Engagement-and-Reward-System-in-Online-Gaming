# Data-Driven-Player-Engagement-and-Reward-System-in-Online-Gaming
ABC is a real-money online gaming company providing multiplayer games such as Ludo. An user can register as a player, 
deposit money in the platform and play games with other players on the platform. 
If he/she wins the game then they can withdraw the winning amount while the platform charges a nominal fee for the services.
To retain players on the platform, the company ABC gives loyalty points to their players based on their activity on the platform.
 Loyalty points are calculated on the basis of the number of games played, deposits and withdrawal made on the platform by a particular player.
 
The criteria to convert number of games played, deposits and withdrawal into points is given as below :
			
Type of Action	Weightage per activity	Formulae	eg.
Deposit of money on the platform	0.01	0.01 * Deposit Amount	0.01 * (1000 RS Deposit) = 10 Points
Withdrawal of money from the platform	0.005	0.005 * Withdrawal Amount	0.005 * (500 Rs Withdrawal) = 2.5 Points
How many more times did a player do deposit than withdrawal	0.001	0.001 * maximum of (#deposit - #windrawal) or 0	0.001 * max((5-3, 0))
= 0.001 * 2
= 0.002 points

where number of deposit = 5
and number of withdrawal = 3
Number of games played	0.2	0.2 *Number of Games Played	0.2 * (50 Total Games Played) = 10 Points
Final Loyalty Point Formula
Loyalty Point = (0.01 * deposit) + (0.005 * Withdrawal amount) + (0.001 * (maximum of (#deposit - #withdrawal) or 0)) + (0.2 * Number of games played)
At the end of each month total loyalty points are alloted to all the players. Out of which the top 50 players are provided cash benefits.
On the basis of above information we have yo calculate the following:
Part A - Calculating loyalty points

On each day, there are 2 slots for each of which the loyalty points are to be calculated:
S1 from 12am to 12pm 
S2 from 12pm to 12am
Based on the above information and the data provided answer the following questions:
1. Find Playerwise Loyalty points earned by Players in the following slots:-
    a. 2nd October Slot S1
    b. 16th October Slot S2
    b. 18th October Slot S1
    b. 26th October Slot S2
2. Calculate overall loyalty points earned and rank players on the basis of loyalty points in the month of October. 
     In case of tie, number of games played should be taken as the next criteria for ranking.
3. What is the average deposit amount?
4. What is the average deposit amount per user in a month?
5. What is the average number of games played per user?

