# The `ensemble` folder

This folder contains the code for the ensemble method.

## `Inference_Ensemble.ipynb` notebook
This notebook contains the code for the ensemble method. It loads saved models, makes predictions on the test set, and combines the predictions using majority voting.

## `Predictions_Ensemble.ipynb` notebook
This notebook contains the code for the ensemble method. It loads saved predictions by each model on the test set, and combines the predictions using majority voting.

## `ensemble_results` folder
Contains the results of the ensemble method:
- `ensemble_predictions.csv`: contains the predictions of the ensemble method on the test set
- `ensemble_wrongs.csv`: contains the wrong predictions of the ensemble method on the test set
- `all_false_negatives.csv`: contains the false negatives that all models have predicted wrong
- `all_false_positives.csv`: contains the false positives that all models have predicted wrong