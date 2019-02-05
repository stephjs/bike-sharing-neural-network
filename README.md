## Building a Neural Network to Predict Bike Sharing Rides

I implemented a neural network trained on historical bike sharing data to predict how many bikes would be needed in the future. Check out the **[full notebook](https://viewd2c7923f.udacity-student-workspaces.com/lab/tree/first-neural-network)**

**Hyperparameters:**
- iterations = 4000
- learning_rate = 0.75
- hidden_nodes = 18
- output_nodes = 1

**Performance:** Training loss: 0.065, Validation loss: 0.164

![progress](https://user-images.githubusercontent.com/18673328/52244824-20148f80-2894-11e9-8c71-6887b1706322.PNG)

**Graphing the Model:**

![training_validation](https://user-images.githubusercontent.com/18673328/52244843-2c98e800-2894-11e9-83a0-39b8d8272d75.PNG)

**Final Thoughts:**

Predictions for December 11 - Dec 21 were close to the actual data. After Dec 21 the model overestimated bike ridership, most likely because it hadn't seen holiday season training examples. 
