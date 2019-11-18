# Machine Learning Playground

Machine Learning Playground facilitates experimentation with simple neural networks by:

* Providing built-in models that can be tuned using a set of hyper-parameters
* Allowing you to create custom models using data that you provide
* Providing graphical feedback on the accuracy of a trained model

**Fully Connected Neural Networks**

<img src="/images/annBasic.png" align="right" />
You create fully connected 3-layer neural networks. The built-in models allow you to specify the number of nodes in the hidden layer. When modeling your own datasets you are free to specify the number of inputs and outputs as well as the hidden layer. In addition, you can specify the activation functions at the hidden and output nodes for your custom models. All models are trained using Stochastic Gradient Descent.
	 
**Hyper-Parameter Tuning**

A key feature of the Machine Learning Playground app is experimenting with a set of hyper-parameters to see how they affect the loss and accuracy of a model. The set of hyper-parameters includes:

* Learning rate
* Momentum
* Mini batch size
* Number of training epochs
* Train/Test % split
* Mean squared error loss vs. Cross-entropy loss

**Bring Your Data**

If you have a specific dataset to explore you can build a model around that data. The app expects the data to be comma-separated rows of numeric values. Inputs are listed first followed by the outputs. For example, a row of data would appear as follows:

<img src="/images/dataLayoutTypical.png" align="center" />
 
You may also specify the activation functions for the hidden and output nodes. These functions include:

* Hyper-tangent
* Log Sigmoid
* Rectified Linear Unit (RelU)
* SoftMax

**Feature Scaling**

Obtaining a good fit for a model often depends on making sure that the feature values have a similar scale. A model will struggle to hit its loss target if some of the features have values such as 100.0 while others have a value of .001. Machine Learning Playground uses a scaling technique known as “Standardization”. The mean and standard deviation are calculated for each feature column. Then, each individual feature is scaled by subtracting its column mean and dividing by its column standard deviation. The formula below illustrates the calculation:

<img src="/images/scalingFormula.png" align="center" />

**Contact**

For Machine Learning Playground support questions please send an email to sandpipertechsolutions@gmail.com

© 2019 Thomas Crampton
