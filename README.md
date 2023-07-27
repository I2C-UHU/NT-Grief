# NT-Grief Dataset
The NT-Grief dataset is a collection of tweets that have been exhaustively labelled for the purpose of conducting supervised classification tasks related to non-traumatic grief messages. The dataset consists of two files: "NTGrief_train.tsv" and "NTGrief_test.tsv". 
Please consider citing the relevant paper if you use this dataset in your work.

# Dataset Description
The dataset was created through a meticulous labelling process involving 2,000 tweets. Each tweet was carefully categorized to form a training dataset suitable for the supervised classification task. As a result of this labelling process, the dataset exhibits an imbalanced class distribution. Out of these tweets, 1395 (69.8%) were assigned the label "0", which indicates the absence of non-traumatic grief messages. The remaining 605 (30.2%) tweets were assigned the label "1", indicating the presence of non-traumatic grief messages.

# File Description

The NT-Grief dataset contains a collection of 2000 tweets, exhaustively labelled for non-traumatic grief messages. Please note that the actual tweet content is not included in the dataset.

The dataset is split into two files:

- NTGrief_train.tsv: This TSV (Tab-Separated Values) file includes tweet IDs and corresponding labels. It consists of 1600 tweets, with 1116 tweets labelled as class 0 (indicating the absence of non-traumatic grief messages) and 484 tweets labelled as class 1 (indicating the presence of non-traumatic grief messages).

- NTGrief_test.tsv: This TSV file has the same structure as the training file and contains 400 tweets. Among these, 279 tweets are labelled as class 0, and 121 tweets are labelled as class 1.

Additionally, we have the full dataset available as "NTGrief_full.tsv." This file contains the complete collection of 2000 tweets, including tweet IDs and corresponding labels, just like the training and test files.

The dataset is well-suited for sentiment analysis, natural language processing (NLP), and research related to grief and emotions. Please note that the dataset provides tweet IDs and labels for each tweet. The actual tweet texts are not included in the files. If you wish to obtain the individual tweets, you can do so using the Twitter API of your choice by querying for the provided tweet IDs.

In the dataset files, you will find two columns, separated by a semicolon, with the following information:

- **ID**: The tweet ID is used to uniquely identify each tweet in the dataset. You can use this ID to retrieve the individual tweets from the Twitter API of your choice.

- **Label**: The label column contains binary values (0 or 1) corresponding to each tweet. A label of "0" indicates the absence of non-traumatic grief messages in the tweet, while a label of "1" indicates the presence of non-traumatic grief messages.


# Label Interpretation

In the NT-Grief dataset, each tweet is associated with a label that indicates the presence or absence of non-traumatic grief messages. The labels are represented as follows:

- Label 0: Absence of Non-Traumatic Grief Messages
  Tweets labelled as "0" signify that the corresponding messages do not contain non-traumatic grief expressions. These tweets may cover various topics, emotions, or sentiments, but they are not related to grief or bereavement.
 
- Label 1: Presence of Non-Traumatic Grief Messages
  Tweets labelled as "1" indicate the presence of non-traumatic grief expressions within the messages. These tweets may include content related to loss, bereavement, sadness, or expressions of grief.
  
It's important to note that the dataset was carefully annotated to distinguish between tweets that contain non-traumatic grief messages and those that do not. Researchers and analysts can utilize these labels for sentiment analysis, natural language processing (NLP), and other tasks related to grief and emotions.

Please ensure to cite the relevant paper if you use this dataset in your research or work.


# Annotation Process

The complete dataset belongs to the project: "Abordaje de la muerte y duelo en redes sociales (Twitter) en tiempos de COVID-19 (RSDUELO-COVID-19)" (IP: Estrella Gualda). Evaluated on 28/7/2020 by the committee (acta 6/20) (Dictamen favorable del Comité de Ética, 1680, n20).

- Estrella Gualda (EG) and E. Begoña García-Navarro (BGN) conceived the original idea.
- BGN, Míriam Araujo-Hernández (MAH), and EG developed the framework.
- EG collected the data from Twitter through GetOldTweets3-optimizedmodified (https://github.com/marquisvictor/Optimized-Modified-GetOldTweets3-OMGOT).
- BGN, MAH, and EG wrote a first annotation guide for qualitative analysis (June 2020) that was applied to annotate the tweets.

        E.B. García-Navarro, M. Araujo-Hernández, and E. Gualda, 
        “Factores protectores y factores de riesgo en duelo sano o funcional en tiempos de COVID-19: Guía de anotación”, 
        Universidad de Huelva. Grupo de Investigación Estudios Sociales E Intervención Social, 2020.

From the complete dataset of the RSDUELO-COVID-19 Project, 9,500 tweets were randomly selected to be binary labeled.

- BGN and MAH did the first annotation of Tweets, with the first aim of distinguishing between tweets containing contents referring to protective factors of non-traumatic grief and tweets not containing that issue, even when the topics "Muerte & COVID-19" were present. EG refereed to resolve disagreements (NTGrief_Full).

- Victoria Pachón-Álvarez (VPA) and Jacinto Mata-Vázquez (JMV), based on the full dataset, built the dataset NTGrief to develop the models for detecting non-traumatic grief messages described in the paper "Automatic Detection in Twitter of Non-Traumatic Grief due to Deaths by COVID-19. A Deep Learning Approach".

# Citation
If you use the NT-Grief dataset in your research or work, please consider citing the following paper:
Automatic Detection in Twitter of Non-Traumatic Grief due to Deaths by COVID-19. A Deep Learning Approach (under review)

[Include the relevant citation here, if applicable.]

## Contact

If you have any questions, feedback, or need further information about the NT-Grief dataset, please feel free to contact me. I'm more than happy to assist you with any queries or provide additional details.

You can reach me via email at vpachon@uhu.es.

If you need access to the dataset that includes the text of the tweets, please let me know, and I'll be glad to discuss the possibilities of sharing that version with you.

I'm also open to collaboration or any suggestions to improve the dataset and its usability. Your input is valuable, and I look forward to hearing from you!

Thank you for using the NT-Grief dataset.

