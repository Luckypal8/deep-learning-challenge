Analysis
For this project, the unnecessary columns were dropped which were EIN and
NAME and the remaining columns were to be considered features. Name was added
back into the second test for binning. The data was then split for training and testing
sets. The target variable for the model was labeled “IS_SUCCESSFUL” and has the value of 1
for yes and 0 for no. APPLICATION data was analyzed and “CLASSIFICATION value was used
for binning. Datapoints were divided into “rare” variables together with the new
value of “Other” for each unique value. Categorical variables were encoded by get_dummies()
after checking to see if the binning was successful.

Overall I had trouble with optimization both in Google Colab and in VSC
I have submitted the coding portion but not able to do three runs due to repeated time out errors.
Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense (Dense)               (None, 30)                590340    
                                                                 
 dense_1 (Dense)             (None, 25)                775       
                                                                 
 dense_2 (Dense)             (None, 1)                 26        
                                                                 
=================================================================
Total params: 591,141
Trainable params: 591,141
Non-trainable params: 0