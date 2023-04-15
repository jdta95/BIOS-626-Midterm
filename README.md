# BIOS-626-Midterm

## Binary Code
Before running the code in "Jonathan Ta Midterm Binary.Rmd", please follow these steps:
1. Make sure you have the following packages installed: caret, knitr.
2. Download the "training_data.txt" and "test_data.txt" data files.
3. Change the working directory in line 19 to the location of the data files.

Once you have completed the steps, you can run "Jonathan Ta Midterm Binary.Rmd".
It will load the training and test data, cross-validate and train a logistic model, run predictions on the test data using the model, and text file "binary_1188.txt" containing the predictions.

* Note the following warnings may occur when training the model:
* Warning: glm.fit: fitted probabilities numerically 0 or 1 occurred
* Warning: prediction from a rank-deficient fit may be misleadingWarning: prediction from a rank-deficient fit may be misleading

## Multiclass Code
Before running the code in "Jonathan Ta Midterm Multi.Rmd", please follow these steps:
1. Run the binary code first. The multiclass code utilizes the "binary_1188.txt" file that is output by the binary code.
2. Make sure you have the following packages installed: data.table, caret, caretEnsemble, doParallel, adabag, MASS, e1071, randomForest.
3. Change the working directory in line 32 to the location of the "training_data.txt", "test_data.txt", and "binary_1188.txt" files.

Once you have completed the steps, you can run "Jonathan Ta Midterm Multi.Rmd".
