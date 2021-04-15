## PartA code

There are multiple files in our notebook. “Assignement2_partA_final.ipynb” is the notebook which contains our final code. We have retained the other files so that it will be possible to keep track of the contributions of each team member.

Our model can be run using the following line of code: “CNN(<num_filters>,<filter_organisation>,<drop_out>,<batch_normalisation>,<data_augmentation>,<kernel_size>,<batch_size>,<num_epochs>,<drop_batch_dense>,<last_2_avgpool>,<dense_sz>,<dp_aft_eachCNN>)”

- <num_filters> : size of the first layer filter
- <filter_organisation>: if set double we just double the filters for the next layers , if same then same number of layers.
- <drop_out>:drop_out is the value of drop_out we will apply
- <batch_normalisation>: if set true we do batch normalisation after each layer,
- <data_augmentation>:if set true we augment the train data,
- <kernel_size>:if set true we augment the train data
- <batch_size>: it's just batch size
- <num_epochs>: num of epochs
- <drop_batch_dense>:if 'both' then we apply dropout followed by batchnormalisation after dense layer , if set 'batch' we do only batch_normalisation after dense layer and if set 'drop' we apply dropout after dense layer
- <last_2_avgpool>:if set true then for last2 Convolutional layers we do avgpool instead of maxpooling
- <dp_aft_eachCNN>: if set true then we apply dropout after every ConV layer else we apply dropout only on last2 convolutional layers
  
In the notebook we have this line , to test the training one may run this with the best hyperparameters mentioned in the report , else there is a cell to load the saved model so you may directly load the model from it and do the testing.

Initially I splitted the train data into train and validation using pypy splitfolders , and stored them on google drive,I made permissions such that anyone with the link can edit, so please add a shortcut of this folder into your drive and run the code. https://drive.google.com/drive/folders/1dx1bYBnnL9PO_y_xH4-5VOcRpmZyTqll?usp=sharing , I gave access to one of the Bethu Sai Sampath Sir.
 
 
