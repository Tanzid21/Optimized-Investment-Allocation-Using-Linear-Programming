# Optimized-Investment-Allocation-Using-Linear-Programming

This project involves developing a data-driven approach to optimize the allocation of a client’s investment portfolio.

#  Problem Statement:

In your unique situation, we were given $800,000 of investment funds to allocate to three funds that you have chosen to invest in. Based on our earlier discussions about your concerns, we have assigned a risk index of 0.05 for you. Adhering to our firm’s guidelines, there is a minimum and maximum percentage per fund that the investment money needs to satisfy in order to be utilized. The challenge here is that each fund will have a different risk rating and annual yield as well so the calculations on how to allocate per fund will all be weighted differently. Our goal is to ensure the optimal solution that your funds will be appropriately placed so that you will receive the highest return rates with all the different factors considered

#  Data Description: 

In our report, we will be using a linear programming model in Microsoft Excel’s Solver for all of our calculations. Some of the terminologies that will be used throughout our report: Simplex Linear Programming Model: This is one of the options of Microsoft Excel’s Solver’s linear programming model. This model is the only model that is relevant for these types of calculations. 

Decision Variable: The unknown quantity or variable we are trying to find out. Constraints: A restriction or limitation of the problem that must be followed or satisfied. Risk Index: The overall result of a risk assessment. It is calculated as a weighted average of the risk ratings for the three funds. Annual Yield: The amount of return from your investment in a year. It will vary depending on how much is invested and the percentage of the yield, as it may vary from fund to fund. Feasible Solution: A solution that satisfies all the constraints of the problem. Objective Function: A function that aims to maximize or minimize the existing profit or production. Optimal Solution: A feasible solution with the largest maximum value or minimum value of the object function

# Methodology:
In our methodology, we will be using Microsoft Excel’s Solver to build a Simplex linear programming model to help us analyze the best course of action for your investment funds. The model is a mathematical technique in which the linear equation will either be maximized or minimized. By deciding on what our decision variable is and taking into account any constraints (or restrictions), the program will help us find the objective function that will help you maximize your annual returns. From there, we will obtain the optimal solution in how much money to invest per fund.

#  Allocation of Alpha, Bravo, and Charlie:

As previously mentioned, to find the allocation of each fund, we must decide upon our decision variable. Since we’re trying to find out how the $800,000 of the investment fund will be split, the variable will be the amount of money that goes into each fund. Next, we looked for restrictions that we should take a note of before using the Solver. The constraints are the restrictions of a problem that are placed and must be satisfied before the allocation happens; they act more or less like rules to be followed. As mentioned before, our firm has guidelines on how much percentage of your investment fund must be added or exceeded. See figure 1 below for the specific minimum and maximum percentages of each fund and please note that Charlie is the only fund without a maximum percentageS

![image](https://github.com/user-attachments/assets/cd988379-5706-4952-93cb-7733ba6ea4cd)

Another constraint that must be taken into consideration is each individual fund’s risk rating. See figure 2 below for the exact values of each


![image](https://github.com/user-attachments/assets/ac9d43e0-b377-4b39-9f3e-89a5732e3245)

While the constraints do not have to be listed in any particular order, it flows better this way: ● Thefirst constraint: The money allocated in Alpha, Bravo, and Charlie added together cannot exceed the investment fund of $800,000. ● Thesecond constraint: Alpha must have a minimum of 20% of $800,000 invested in it. ● Thethird constraint: Alpha cannot have more than 45% of $800,000 invested in it. ● Thefourth constraint: Bravo must have a minimum of 15% of $800,000 invested in it. ● Thefifth constraint: Bravo cannot have more than 50% of $800,000 invested in it.● Thesixth constraint: Charlie must have a minimum of 30% of $800,000 invested in it. ● Theseventh constraint: the maximum risk calculated. 
These constraints will be inputted into the Solver for calculations. You may also find the constraints of this function listed in figure 3 below: 

![image](https://github.com/user-attachments/assets/a2c82260-f7d4-4b47-b851-10b54a4fe3ab)

After inputting all the constraints into the Solver program, the result is illustrated in figure 4:

![image](https://github.com/user-attachments/assets/1aa87987-ef02-44d6-bcae-83f36b69dc20)

For the optimal solution, or basically the maximum annual returns, we at XYZ firm recommend that $240,000 should be allocated to Alpha, $120,000 should be allocated to Bravo, and $440,000 allocated to Charlie. There is a potential risk of $40,000 in the investment but your maximized annual return more than doubled that amount. The maximized annual return will be $91,200, which is 11.4% of the initial fund of $800,000 that was invested.

# Situation 1: Increase in Risk Index:

Nowthat we have the allocation of the funds suggested and the risk and annual returns stated, we would like to go over with you on what would happen should certain scenarios change. If we were to increase the risk index assigned earlier from 0.05 to 0.06– with all the constraints staying constant– we see that the allocation of funds is distributed differently than before. The Solver indicates to us that Charlie should lose $100,000 investment funds from the previous suggested allocation, bringing it from $440,000 down to $340,000 and the $100,000 will get reallocated to Alpha instead. Interestingly, by increasing the risk index and shifting the allocation of the funds due to it, we see that the actions get rewarded by annual returns increasing as a result.Therefore in this specific situation, we recommend that you should invest $340,000 in Alpha, $340,000 in Charlie, and keep the Bravo fund the same as before ($120,000). By changing the previous recommendations, the returns would increase by $10,500, going from the original amount of $91,200 up to $101,700. This will make the annual yield increase from 11.4% to 12.7%, respectively, netting a yield increase of 1.3%. Please see figure 5 for reference

![image](https://github.com/user-attachments/assets/983d65ec-44a5-4775-a148-b29d468b5c9d)

#  Situation 2: Decreases in Annual Yield

In today’s current economy, there runs a possibility that a fund may choose to lower their yield due to inflation or other economic-related reasons. For example, should the Alpha fund revise
their yield down from 18% to 17.5%, we would see as a result that although the allocation of all three funds and the risk amount do not change (from figure 4), the returns have decreased. The investment return’s value would decrease by $1,200, pushing the previous investment returns of $91,200 down to $90,000. Please see figure 6 for the possible changes that may occur if the annual yield were to be revised down to 17.5%

![image](https://github.com/user-attachments/assets/41a76891-9b72-4ffa-8dfa-dd2826fb38ef)

Another example is if Alpha's annual yield fell further down to 16% instead, the result shows that the allocation of the three funds and annual returns are to decrease while the risk remains constant. Alpha’s recommended allocation will drop to $160,000 and Charlie’s allocation will also drop to $360,000. On the contrary, the recommendation of Bravo’s fund will more than double from the original recommendations, significantly increasing the suggested fund of $120,000 to $280,000. Though due to Alpha’s annual yield reducing to 16%, the investment returns diminish to $87,600. Please see figure 7 for reference

![image](https://github.com/user-attachments/assets/e9cab9ab-f7d2-4544-988f-c865321bebce)

# Situation 3: Your Concerns are Our Concerns
Your concerns are our top priority here in XYZ firm and we value you as our customer. We want you to have all of your concerns addressed in a satisfying, timely, and professional manner. Earlier this week, we had spoken briefly over the potentials of Alpha fund. As a quick recap, it is a fund that boasts a higher risk-reward system where the more you risk, the higher the potential pay-out would be at the end of the year. You’ve expressed concerns over Alpha running a risk above your comfort zone, so in this section, we will dive into one of the suggestions you had given to us: The investments allocated to Alpha should not exceed the investments allocated to Bravo. To update the newly added information that the original situation did not have, we have inserted Alpha as an amount that cannot be greater than or equal to Bravo’s allocated funds in the Solver program as a new constraint (restriction). After running the program, the new allocation of the fund reads as $200,000 in Alpha, $200,000 in Bravo, and $400,000 in Charlie, compared to the original distribution recommendation of Alpha’s $240,000, Bravo’s $120,000, and Charlie’s $440,000. Please see figure 4 and figure 8 for references on the previous and new allocations, respectively.


![image](https://github.com/user-attachments/assets/3da67c77-d38e-4da9-8105-227f1b7fe9e5)

The results show that the returns have decreased by $200, resulting from $91,200 to $91,000, but the risk amount stays the same at $40,000

# Results

So what does going over all these different types of situations all mean and why does it matter? There are many reasons why people refer to professionals for investment advice. Occasionally you may find yourself willing to deal with higher risk for higher reward such as situation 1 or perhaps you may want to play it safe in an exchange for lower returns instead. Sometimes, you may also find yourself in situation 2 where there may be additional changes to a fund where the fund’s risk rating or annual yield could be revised higher or lower than its original amount. This may influence how you would want to redistribute your funds. Our job is to keep our clients informed so that they may confidently make the best possible decision with their investments. Here is a recap of the two options we had gone over previously: ➢ First Option: With the original conditions depicted in figures 1, 2, 3, and 4; we recommend investing $240,000 in Alpha, $120,000 in Bravo, and $440,000 in Charlie. With this recommendation, you would be risking $40,000 and your annual returns will be $91,200. ➢ SecondOption: This result is the one you have suggested where Alpha’s funds should not exceed Bravo’s as depicted in figure 8. This figure recommends investing an equal amount of $200,000 in Alpha and Bravo, and $400,000 in Charlie. With this recommendation, you would be risking $40,000 for the annual returns to be $91,000.

# Our Recommendations

In XYZfirm, we strongly recommend that you should go with the first and original option. With the first option, you will be risking the same amount of money as the second option ($40,000) and receive $200 more in returns ($91,200 instead of $91,000). Our data shows that allocating more money on Bravo, the safer fund, does not provide any benefits as the risk amount stays the same. Instead, doing so would diminish returns



