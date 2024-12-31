# Assignment-7
Batch wise model development
# Assignment Targets:
  1. Best Test Accuracy: 99.4%
  2. No of Epochs - < 15
  3. No of Parameters < 8,000

# Batch 1 
# Target
  1. Creating the Train & Test Dataset
  2. Understanding the Data Statistics
  3. Plain vanila model training & testing
  4. Running Epoch & Plottign results

# Results
  1. Parameters: 6,379,786
  2. Best Train Accuracy: 99.94% (Epoch 12 & 13)
  3. Best Test Accuracy: 99.32% (Epoch 9 & 10)

 # Analysis
 Created the model code in a proper structure with plain vanila model. Achieved good results within 15 Epochs on both training & test.

# Batch 2 
# Target
  To Convert the raw model to a defined skeleton and perform the following:
  1. Sqeeze & Expand
  2. Channel reduction (32--> 10)
  3. Adding Max pooling
  4. Adding Batch Normailisation
  5. Adding Dropout

# Results
  1. Parameters: 10,970
  2. Best Train Accuracy: 99.29% (Epoch 12)
  3. Best Test Accuracy: 99.14% (Epoch 14)

 # Analysis
 By introducing Max pooling, Batch Normalisation & Dropout, the gap between the train & test accuracy reduced. It also reduced the parameter count from million to 10K.
 However, within 15 epochs could not achieve the assignment target of 99.4% test accuracy within 8K parameters.
