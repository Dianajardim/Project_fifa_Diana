Scenario: We are running the player management for the club AC Milan, and we want to see how well we pay our players and if there's any salary change that needs to be made.

Goals:

We want to see how well our players are being paid;
We want to understand the global salary status for players;
We would like to see if we can identify some overpaid players and if it is better to make some transfers to maximize our outcome
Process:

We check the null data, and remove all the duplicates.
We want to generate a model to predict Wage(in Euro)
We need to compare the predicted wage made by the model to see of we overpaid our players
We want to have a general idea of how we want to decide if we want to transfer the players in our club.
We first need to see what are having high correlation with Wage(in Euro)
We take into consideration of the factors that might be correlated and better not to be included in the predictors to avoid multicollinearity
We split the dataset into training data(the rest) and test data(AC Milan)
The independent variables are standardized
We test some models to determine which model fits better
We use the model to predict our players' Wage and compare it to the current wage.
We check the number of players being good at certain positons(generalized into 4 positions) to see if there are some players with less overall/potential values and high wage.
We filter the players globally to find potential players that are good at this position and less or even no release clause
