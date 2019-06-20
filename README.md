# Task-2

### My process for this task:

#### 1 - Use 'Visualization and Base model.ipynb' to explore the data, here are some takeaway:
  - The training data is not balanced, we have 3424 of one class and 276 of the other class, therefore i decided not to use accuracy as our performance metric and choose to use AUC, while i think using precision/recall would've been better for this dataset but i don't have enough information about the dataset of which class we care about more so i've just used AUC and got good reulst.
  - 'variable19' in the training dataset is just copy of the target variable, we have to drop it

#### 2 - Use 'pre_process data.ipynb' to do some cleaning and feature engineering.
#### 3 - Use 'train_lgb.ipynb' to traing lightgbm model, after hyper-parameters tuning i managed to get 0.98 AUC on the training set and 0.96 AUC on the validation set
#### 4 - Use 'train_random_forest.ipynb' to train another model (random forest), i only managed to get 1.0 AUC on the training set and 0.86 AUC on the validation set, i also tried some other linear models but didn't get good result, so it seemed like tree-based models is best for this dataset.

