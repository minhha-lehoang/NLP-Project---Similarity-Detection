# The `train` folder

This folder contains all the necessary files for training the Cross0E model.

## `training_notebooks` folder
Contains the notebooks used for training the models, each notebook is named after the model it trains in the format `CE_{model_name}.ipynb` (CE stands for Cross-Encoder).

## `training_results` folder
Contains the results of the training process, each folder is named after the model it trains in the format `{model_name}`. Each folder contains:
- `model` folder: contains the trained model
- `plots` folder: contains the plots of the training process
- `prediction_{model_name}.csv`: contains the predictions of the model on the test set
- `wrong_preds_{model_name}.csv`: contains the wrong predictions of the model on the test set
- `classification_report_{model_name}.txt`: contains the classification report of the model on the test set