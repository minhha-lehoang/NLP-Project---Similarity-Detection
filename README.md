# NLP-Project-Similarity-Detection

## Introduction
This repository contains the code, models, and output files for the mini project of the course INT3406E - Natural Language Processing - class 21, done by group 14.
  
## Group members
| Name               | Student ID | Email               |
|--------------------|------------|---------------------|
| Le Hoang Minh Ha   | 21020621   | minhha.lehoang@gmail.com |
| Nguyen Dieu Nhat   | 21020656   | dieunhat@gmail.com |

## Project description
Semantic Similarity Detection in Natural Language Processing is pivotal for measuring the level of text resemblance and has been applied in various applications. In this experiment, we adopt an Ensemble Methods
from three BERT-based models to take advantages of their complementary strengths and weaknesses. We conduct our methods on the Microsoft Research Paraphrase (MSRP) ([Dolan and Brockett, 2005](https://aclanthology.org/I05-5002/)) dataset, achieving the best accuracy of 0.9125 and F1-score of 0.9003.

The report can be found in the [Group_14-Sentences_Semantic_Similarity_Detection_with_Ensemble_Methods_integrating_BERT-based_models.pdf](https://github.com/minhha-lehoang/NLP-Project-Similarity-Detection/blob/afec318b34a8f756f0e6eaf834f942c4ec7f4a23/Group_14-Sentences_Semantic_Similarity_Detection_with_Ensemble_Methods_integrating_BERT-based_models.pdf) file contained in this repository.

## Repository structure
### The [data](https://github.com/minhha-lehoang/NLP-Project-Similarity-Detection/tree/main/data) folder
Contain the original dataset in `.tsv` format and the preprocessed dataset in `.csv` format.

### The [train](https://github.com/minhha-lehoang/NLP-Project-Similarity-Detection/tree/main/train) folder
Contain the Jupyter notebook files for training the models and the training results output files.

### The [ensemble](https://github.com/minhha-lehoang/NLP-Project-Similarity-Detection/tree/main/ensemble) folder
Contain the code for the ensemble method.

### The [figures](https://github.com/minhha-lehoang/NLP-Project-Similarity-Detection/tree/main/figures) folder
Contain the figures used in the report.

____
**NOTE**: this branch contains the training results file *without* model checkpoints. The training results files including model checkpoints can be found in this dataset: https://www.kaggle.com/datasets/lehoangminhha/training-results.

To clone this repository on local device, use:
```
git clone https://github.com/minhha-lehoang/NLP-Project-Similarity-Detection.git --branch light --single-branch NLP-Project-Similarity-Detection
```
