1. How many neurons and layers did you select for your neural
    network model? Why?

ANS: Hidden layer 1 has 50 nodes and hidden layer 2 has 30 nodes. In total,
    there are 80 nodes. I chose to use 80 nodes because it is 
    recommended to use double the amount of inputs as our amount
    of nodes. In this case our "inputs" (i.e. len(X_train[0]))
    is 40. Thus, our nodes should be twice as much
    (i.e total nodes = 2 * len(X_train[0])).

2. Were you able to achieve the target model performance?
    What steps did you take to try and increase model performance?

ANS: I was not able to achieve the target model performance(75% accuracy).
However, I was able to get very close to our target with a 73% accuracy score.
I went ahead and determined which columns needed to be modified and/or dropped.
After cleaning our data, I went ahead and began to build the neural network.

3. If you were to implement a different model to solve this
    classification problem, which would you choose? Why?

ANS: I would use a Support Vector Machine because it uses classification 
algorithms for two-group classification problems. It would be perfect
for this assignment because we are essentially working with two groups.
