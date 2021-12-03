# Master's-Thesis---Mateusz-Sabatowski
#Abstract of a study: 

Common in psychology and philosophy distinction between moral action and action that is not a subject of moral judgment did not receive enough investigation. This study consists of a machine learning classification task with the use of the HerBERT model for Polish language performed on a prepared dataset of description of actions. Examples of such descriptions were collected from the internet available source and annotated with four categories. These categories are: moral action, neutral/non-moral action, non-human action, collective action. Main hypothesis relies on the assumption that useful and apt categories allow for reliable and precise identification of examples of these categories. This means that a high score on a classification task performed on prepared data partially indicates that described categories constitute a useful definition of distinction between moral and neutral/non-moral action.

#Information on notebooks and data: 

This repository contains two notebooks and a dataset consisting of over 2000 examples annotated with four categories. One notebook consists of a fine-tuned HerBERT model for sequence classification with obtained results. Results achieved in this model are of main focus in this study. Second notebook contains the HerBERT model without fine-tuning. Results achieved in this model constitute baseline  scores of classification.

To use both notebooks, one only needs to upload a prepared dataset to google colab memory and run all code cells. The results are presented in the last cell of each notebook. 

tIn the notebook with fine-tuned models, new training, validation and test sets are created with random examples every time this code is run. Although this causes slightly different results of classification, differences are not very significat. 
