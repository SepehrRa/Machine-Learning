# Machine-Learning

Hello Everyone,

I uploaded my homework of machine learning online course which is taught by Professor Andrew NJ from Stanford University. 

All codes can be run by MATLAB/Octave (4.4.0 or higher) and to give more information about each practice one document file is prepared.
It would be better to read it first and get familiar with functions.

Just you need to run the main function which is named by “exNUM.m” for example ex5.m 

Here are brief information of each excerice:

HW1: Linear regression. 

In this exercise, I implemented a linear regression method and get to see it work on sample data.

HW2: Logistic Regression.

In the first part of the exercise, I built a logistic regression model to predict whether a student gets admitted into a university. 
I used a linear decision boundary to classify data. In the second part of the exercise, I implemented regularized logistic regression
to predict whether microchips from a fabrication plant passes quality assurance (QA). 
Nonlinear decision boundary and regularizing term are used.

HW3: Multi-class Classification & practical use of Neural Networks.

In the first part of the exercise, I used the previous implementation of logistic regression and apply it to one-vs-all classification to recognize handwritten digits (from 0 to 9). And finally, I got 95% of training set accuracy.
In the next part of the exercise, I used MPL Neural Networks library to do the previous task and surprisingly accuracy reached 97%! 

HW4: Neural Networks Learning Algorithm.

In this exercise, I built the whole of the MLP network by myself and used backpropagation algorithm calculate the weight of the network. I got 97% accuracy again on the training set of HW3 but a little slower than the Neural Networks library.

HW5: Regularized Linear Regression.

In this exercise, I implemented regularized linear regression and use it to study models with different bias-variance properties. With this knowledge, I can choose proper initial condition regarding the characteristics of each data systems.

HW6: Support Vector Machines (SVM).

In the first half of this exercise, I used support vector machines (SVMs) with various example 2D datasets. Experimenting with these datasets helped me gain an intuition of how SVMs work and how to use a Gaussian kernel with SVMs.
In the second part of the exercise, I implemented SVMs to build your email spam filter.

HW7: K means Clustering & Principal Component Analysis (PCA).

In this exercise, I implemented the K-means algorithm and used it for image compression. Firstly it helped me gain an intuition of how the K-means algorithm works. After that, I used the K-means algorithm for image compression by reducing the number of colors that occur in an image to only those that are most common in that image. 
Next, I used principal component analysis (PCA) to perform dimensionality reduction. I first experiment with an example 2D dataset to get intuition on how PCA works and then use it on a bigger dataset of 5000 face image dataset.

HW8: Anomaly Detection and Recommender Systems

Anomaly detection is a useful algorithm to find and ignore the data which is abnormal. It can help us to improve our algorithm performance. In this exercise, I implemented an anomaly detection algorithm to detect anomalous behavior in server computers. The features measure the throughput (MB/s) and latency (ms) of the response of each server.
In the next part, I used collaborative filltering to build a recommender system for movies. This system will recommend new movies based on the movies which users rate previously. 
