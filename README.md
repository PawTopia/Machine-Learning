<img src="https://github.com/PawTopia/Mobile-Dev/assets/115199962/136c74f7-d841-447f-abe0-83237297efa5" height="90%" /> 

Pawtopia
==================
This is the repository for Pawtopia Machine Learning for Bangkit Academy H2 Capstone Project

This repository contains 2 folders: **dataset** and **symptoms-model**. The model trained using **TensorFlow** and **Support Vector Machine (SVM)**
The **symptoms-model** contains 2 Jupyter Notebook files: **data-preprocessing** and **model-train**, 1 h5 model file and 1 pkl model file

# Symptoms Model
The model aims to accurately classify 12 dog diseases based on symptoms given using ANN. The tabular dataset was forked from [this repository](https://github.com/1zuu/Doggy-Disease-Detection/blob/master/data/symtomdata.csv)
| **Information** | **Value** |
| --- | --- |
| Preprocessing Technique | One Hot Encoding |
| Model Structure | Two Dense (relu activation) layers and One Dense (softmax activation) layer |
| Model Input | List of symptoms |
| Model Output | Classification of Dog Diseases |
