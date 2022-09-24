# Medical_Code_Prediction-
Use BERT , Clinical-BERT and Longformer to do the medical code prediction

## Usage:
1. You need to get familiar with the google colab environment, and load the notebooks above to your google drive online.
2. Get the access to the MIMIC III dataset from [here](https://physionet.org/content/mimiciii/1.4/)
3. Open a new notebook in google drive and clone the [CAML model](https://github.com/jamesmullenbach/caml-mimic), which is a classical model for this task and contain many useful codes we need in the following steps.
4. Read the introduction of each notebooks and choose the one you are intrested in. (you may need to change some urls or links in the notebooks to run notebook successfully.)

## Introduction for each notebook
CAML_RUN: to run the [CAML](https://github.com/jamesmullenbach/caml-mimic) model by google colab environment.  
Find_MN: extract the patients who suffer from therioma.  
LAAT_Run: run a classical LSTM-based model for medical code prediction by colab, you could see more infomation from [here](https://paperswithcode.com/paper/a-label-attention-model-for-icd-coding-from).  
Transformer_MCP_xxxxx : a completed pipeline for fine-turn different pretrained models to do the task, you coud see more information in each notebook.  
Data_Augmentation_sub_1,2,3 : The code used for preparing augmented data, you could see more infomation about the way i do the data augmentation in my research report.  


if you have any problem with these codes, do not hesitate to send the email to me (tengfei.cui19@studetn.xjtlu.edu.cn , cuitengfei2021@gmail.com)

