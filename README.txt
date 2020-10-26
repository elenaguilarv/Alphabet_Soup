Challenge Module 19 - Written Analysis

How many neurons and layers did you select for your neural network model? Why?
After I prepared the data, I attempted to play with the hidden layers in hopes that it would directly improve my model's performance. I read online that keeping the hidden layer between the size of the input and output layer is important and also picking a number that does not make the model prone to overfitting. Unfortunately anything I would change would not change performance of my model. It had a consistent output in loss and accuracy score (more detail below). 

Were you able to achieve the target model performance? What steps did you take to try and increase model performance?

I did not achieve target model performance. My accuracy score did not rise past 0.532 but it did improve somewhat after I went back to the earlier stages of my code to drop more columns and bucket some values for specific features. Initially, I had not dropped the identification columns to test the score without preparing the data, and I got a memory error/ memory allocation issue because my data could not scale so much information. 

If you were to implement a different model to solve this classification problem, which would you choose? Why?

I would choose the neural network model instead, given some more research and an encounter with the source link listed below. Because of its specific ability to cluster or group data that is similar and classify data groups, it could be more useful for a model of binary classification. It also allows for connection and weights which has a direct impact on the lowering of the loss score. Using the deep learning model, my loss score was fairly high, at .691.

Source:
https://www.upgrad.com/blog/deep-learning-vs-neural-networks-difference-between-deep-learning-and-neural-networks/#:~:text=While%20Neural%20Networks%20use%20neurons,responses%20present%20in%20the%20brain.