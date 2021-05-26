# Classifcation of MNIST Handwritten text data using SkLearn's LogisticRegression() and also using ANN that was built from scratch

### Requirements
  Install Tensorflow

  Install Keras

  Install sklearn
### KeyPoints
1. The idea of this exercise is to leverage the importance of using ANNs for classification tasks when we have huge data
2. Also MNIST data when fitted to any model converges faster as the data is very ideal. So there is a high chance of overfitting, we need to penalize the weights using 'L1' or 'L2' Regularizer in case of Logistic Regression. 
3. In the same way it is even more easier to do this using DropOuts in case of building ANNs. Try different dropout rates and see for yourself how accuracy changes. 
4. See from the Linear Regression module https://github.com/nandakishorem777/MLDLForALL/blob/main/Linear_Regression/Linear_Regression_Using_Sklearn_and_TF_Keras_ANN.ipynb how we built the network and how the current ann module is different from that. Especially observe the output layer. We do not have an activation function when we are doing regression but we need to have either 'softmax' or 'sigmoid' when we are fitting a classification model
5. Also you can understand the differnce between using 'sparse_categorical_crossentropy' and 'categorical_cross_entropy' as a loss function from this exercise. 
6. Take a look at my youtube video https://youtu.be/5RSRRosUmkA?t=944 to understand classification and logistic regression essentials. 

Please subscribe to my YouTube channel https://www.youtube.com/channel/UCdt6ftfnQhH_KmiUswYhxzg for more useful content. 
