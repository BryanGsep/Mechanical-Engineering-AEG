# Mechanical-Engineering-AEG

## Dataset

Research data include three component question answers which is collected from three Indonesia Universities (SU, ITB and UGM). There are three scoring level for each question (Level 0, Level 1 and Level 2).

## Research MileStone

1. Data Augmentation Method selection

Choosing between two state of art automatic data augmentation methods. They are based on two models (chatGPT fined-tune, and T5 model)

<a href="./AEG/Question_1_1/Data_Augmentation_Selection/">Data Augmentation Code</a>

2. Data Prepprocessing Method

Choosing between three preprocessing method (Removing stopword, Lemmatization, Part of Speech) and compare their performance with data without using any preprocessing method

<a href="./AEG/Question_1_1/Preprocessing_Selection/">Preprocessing Code</a>

3. Compare Model Performance

Comparing performance of (BERT, distillBERT and RoBERTa) as an AEG model in regarding with training time, prediction time, and predicition accuracy
