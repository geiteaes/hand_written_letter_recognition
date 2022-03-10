# Visual Concept Learning for Hand Written Letter Recognition 
An unsupervised machine learning algorithm to recognize handwritten alphabet 

Supervised learning has been proven to give a lot of benefit in machine learning world. However, this model needs a lot of data with appropriate label which may not be available for certain casses. Not because it is labor intensive (real human has to assign real label), the amount of data that needs to be labeled increased exponentially especially in the era of big data. For this reason, unsupervised learning becoming more favorable.  
 
In this project, several model will be introduced to overcome hand written recognition task. EMNIST handwritten dataset will be used to train and test the models. Deep Belief Network (DBN) with several layers is being trained. Each DBN model then paired with linear readout. To observe DBN effectiveness, Feed Foward Neural Network (FFNN) and Perceptron model is also being trained and tested. Furthermore, model robustness against noise will also be explored. There are two kind of noise that will be introduce, gaussian noise and adversarial attack. 

## Confusion Matrix 
<img src="confusion matrix.JPG">

## Model Comparison Summary 
<img src="model comparison.JPG">
