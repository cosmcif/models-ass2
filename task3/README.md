# Updpated data

## Model 1: Train vs Validation accuracy

The best model (found at `model_cut_1.pth`) reached the best validation accuracy at epoch 58 with validation_accuracy: 0.8948948948948949. Below, the plot of the training and validation accuracy.

![image](https://github.com/cosmcif/models-ass2/assets/75504103/7ea39449-43c5-4eff-93d1-584541bca688)

From this data only, I would expect the model to recognize images never seen before with an accuracy around 80-85%.

## Model 1: Testing with new data
After running the model on new data never seen before, I obtained an average accuracy of 0.8389152275180027. The detailed list of accuracy results in the testing phase of this model can be found in the file data.txt. 

## Model 2: Train vs Validation accuracy

The best model (found at `model_cut_2.pth`) reached the best validation accuracy at epoch 5 with validation_accuracy: 0.96996996996997. Below, the plot of the training and validation accuracy.

![image](https://github.com/cosmcif/models-ass2/assets/75504103/cfdf668b-682d-4c8c-a4a1-1c41554179f5)


From this data only, I would expect the model to recognize images never seen before with an accuracy around 90-95\%.

## Model 2: Testing with new data
After running the model on new data never seen before, I obtained an average accuracy of 0.9485790570740931. The detailed list of accuracy results in the testing phase of this model can be found in the file data.txt. 

## Comparing performance
After comparing the models, I get the following results.

- `T-statistic: -11.602673028233815`
- `P-value: 2.769849437979004e-06`

The difference between model 1 and model 2 is statistically relevant. It is still valid what is present on the report regarding the difference between the two models. I will copy it below.

`The difference is likely due to the fact that the second model has more convolutional layers which allow it to better classify and categorize images by extracting the features.`
