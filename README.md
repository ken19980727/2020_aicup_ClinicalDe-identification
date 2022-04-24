# 2020_aicup_Clinical_De-identification
Provide outpatient dialogues and related interviews collected from the outpatient clinics of Chengda Hospital, and manually mark the privacy content and types in the dialogue data. The data are divided into training set, construction set (development set) and test set.
The main goal of this competition is to identify and extract content containing private information from the dialogue between doctors and the public, and to classify what kind of privacy the content belongs to. Use F1-Score to evaluate the accuracy of the prediction results of the contestants on the test corpus.
## Dataset (final ver.)
Training Set : 200 dialogues
Testing Set : 158 dialogues
## Algorithm
* CRF
* BiLSTM
* BiLSTM+CRF
* RoBerta
* BERT-Chinese
## Awards
![](https://i.imgur.com/ivJrrTQ.png)
https://aidea-web.tw/topic/d84fabf5-9adf-4e1d-808e-91fbd4e03e6d
## Evaluation Methods
![](https://i.imgur.com/XzHdesT.png)
