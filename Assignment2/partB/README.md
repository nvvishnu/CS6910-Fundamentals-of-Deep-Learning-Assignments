## PartB code

 “Assignement2_partB_final.ipynb” is the notebook which contains our final code
 
 Our model can be run using the following line of code: fun(model_name,retrain_top_layers_percentage,<augmentation>,epochs,optimizer)
 
 - <model_name> : Is just of the name of model
 - <retrian_top_layers>: it's percentage of top_layers of the model that we will retrain/100
 -  <augmentation>: If true then we'll augment the data
 -  epochs: it is  the number of epochs
 -  optimizer: it is the optimizer ('sgd','adam',etc..) that we want to use , 
 
 
 In the notebook we have this line , to test the training one may run this with the best hyperparameters mentioned in the report.
 Initially we splitted the train data into train and validation using pypy splitfolders , and stored them on google drive,we made permissions such that anyone with the link can edit, so please add a shortcut of this folder into your drive and run the code. https://drive.google.com/drive/folders/1dx1bYBnnL9PO_y_xH4-5VOcRpmZyTqll?usp=sharing , I gave access to one of the TA Bethu Sai Sampath Sir.  
