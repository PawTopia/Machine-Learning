Pawtopia
==================
This is the repository for Pawtopia Machine Learning for Bangkit Academy H2 Capstone Project

This repository contains 2 folders: 'dataset' and 'symptoms-model'. The model trained using TensorFlow and Support Vector Machine (SVM), and the dataset can be found in 'dataset' folder.

# Symptoms Model
The model aims to accurately classify 12 dog diseases based on symptoms given using ANN. The tabular dataset was forked from [this repository](https://github.com/1zuu/Doggy-Disease-Detection/blob/master/data/symtomdata.csv)
| **Information** | **Value** |
| --- | --- |
| Preprocessing Technique | One Hot Encoding |
| Model Structure | Two Dense (activation='relu') layers and One Dense (activation='softmax') layer |
| Model Input | List of symptoms |
| Model Output | Classification of Dog Diseases |