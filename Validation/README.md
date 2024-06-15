##Validation set

Until learn about validation, we use test_set for evaluate model.

However, if you repeatedly use test_set and find the optimal model, there is a disadvantage that a model that fits test_set is created.

So from now, we use validation set. We can separate train set fot make this like test_set.

Example
    #Separate 20% from train_set for test_set and again 20% for validation set. 
    #Find optimal hyperparameter use train_set(60%), validation set(20%)
    #After find, give the final score as train_set + validation set(80%)  and test_set(20%)
