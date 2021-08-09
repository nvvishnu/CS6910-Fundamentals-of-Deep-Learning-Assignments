## CS6910-Assignments
This is the python code for Assignments of CS6910(Deep Learning) course developed by V Vishnu Kiran(CS18B067) and Meesa Shivaram Prasad(CS18B056).

# Assignment 1: 

Check the direcotry "Assignment 1"

There are multiple files in our notebook. “Assignement1_Final_Sweep.ipynb” is the notebook which contains our final code. We have retained the other files so that it will be possible to keep track of the contributions of each team member. 

Our model can be run using the following line of code:
“[weights,biases] =backpropagation(<train_X>,<train_Y>,<num_epochs>,<num_hidden_layers>,<sz_hidden_layer>,<learning_rate>,<optimizer>,<batch_size>,<weight_initialisation>,<activation>,<weight_decay>,<validate_X>,<validate_y>)”

<train_X> 		- 	Training dataset 
<train_y> 		- 	Expected output of training dataset
<num_epochs>	 	- 	Number of epochs
<num_hidden_layers> 	- 	Number of hidden layers
<sz_hidden_layer> 	- 	Size of every hidden layer
<learning_rate> 	- 	Learning rate
<optimizer>		- 	Optimizer
<batch_size> 		- 	Batch size
<weight_initialisation>  - 	Weight initialisation
<activation>  		- 	Activation function
<weight_decay> 	- 	Weight decay(L2 regularization)
<validate_X>		- 	Validation dataset
<validate_y>		- 	Expected output of validation dataset

We have included <validate_X> and <validate_y> as parameters to backpropagation function to log the validation accuracy and loss for each epoch in backpropagation function


This returns the trained weights and biases of the model as a list of arrays(We decided to use a list for weights to be able to support different numbers of neurons in each hidden layer.

The model can be evaluated using the following lines of code:
“print(accuracy(<data_X>,<data_y>,weights,biases)) #Print the accuracy of our model
print(cross_entropy_loss(<data_X>,<data_y>,weights,biases)) #Print the cross entropy loss of our model”

Here, <data_X> refers to X dataset and <data_y> refers to Y dataset. 
For example, using 
<data_X> = trainX and <data_y> = trainy gives us training accuracy and cross entropy loss
<data_X> = validateX and <data_y> = validatey gives us validation accuracy and cross entropy loss

# Image Classification 

Check the directory "Assignment 2"
  
# Transliteration

Check the directory "Assignment 3"
