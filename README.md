<img src="https://user-images.githubusercontent.com/49169365/196077264-112f7365-c7a9-4f39-9ca7-201ab0c3bc5c.png" height = "250" width="250" class="center">

# Wise Translator
### **Sequence-to-Sequence Semantically and Contextually Intellectual Machine Translation from English to Urdu and vice versa**

## About
In this project, we are planning to develop a bi-lingual translation application which will take the text in either Urdu or English, and will provide the concise and relevant translation in other language respectively.

With everything moving towards automation in today’s world, we saw a gap since there is a dearth of online real-time applications that translate between Urdu and English text except for a few. We aim to develop a web application which will translate Urdu text to English and vice versa. The main use case of this application is to act as a bridge between the two languages. As we are working on the pure concepts of NLP (Natural Language Processing) and we have targeted these two specific languages one is English an international language and other one is Urdu our national language. There is sufficient work done on Urdu at academic level as well as National level but by this project, there will be a chance and opportunity that people will get help from this and can use our provided API and gathered datasets for their development concerns and with the help of that learning, many people will get served and become able to explore this side of computer science and its applications.

## Objectives 
* To provide a platform for quick translation which is necessary for the spread of knowledge and ideas 
* To lay out an initiative which will help others in future 
* To help subtitle generation and API will help the people to get subtitles easily
* To make Urdu a stand able language because it is our national language which needs to be prevailed

By now after achieving our goals, essential knowledge about TensorFlow, Python, Google Colab and different techniques of NLP (Natural Language Processing) has been attained. And with that exposure, we became able to apply the core Deep Learning and machine learning techniques for training our Transformer (Model). And we learned how to gather datasets, how to clean them and there were many difficulties as well. But, in the end, we’ll say we have learnt a lot by this project. We intend to keep it on as learning is just like improving youself everyday.

The datasets we’ve gathered so far are cited in our report. We've gathered almost 2.5Million parallel sentences data till date. We’ve trained our model on it using GPUs with different batch sizes and it is giving efficient results. 

## Implementation Details
### [Understanding the BLEU Score Evaluation Metric](https://cloud.google.com/translate/automl/docs/evaluate#bleu)
BLEU (BiLingual Evaluation Understudy) is a metric for automatically evaluating machine-translated text. The BLEU score is a number between zero and one that measures the similarity of the machine-translated text to a set of high quality reference translations. A value of 0 means that the machine-translated output has no overlap with the reference translation (low quality) while a value of 1 means there is perfect overlap with the reference translations (high quality).

It has been shown that BLEU scores correlate well with human judgment of translation quality. Note that even human translators do not achieve a perfect score of 1.0.


![image](https://user-images.githubusercontent.com/49169365/196080045-51ead3f3-fcc9-4b37-9af1-12dee7905307.png)

Source: [Interpretation](https://cloud.google.com/translate/automl/docs/evaluate?cloudshell=false#interpretation)


## Progress/Results
### English to Urdu Model
* Trained on 2.3 millions parallel sentences dataset for 5 epochs
* BLEU Score achieved approximately 32 

### Urdu to English Model
* Trained on 2.3  of millions parallel sentences dataset for 5 epochs
* BLEU Score achieved approximately 31


## Snapshots
### Wise Translator's Translation (1)
![aa](https://user-images.githubusercontent.com/49169365/196082017-8e2c1c9d-b7d8-47a4-8b9d-ee0389c275ce.PNG) 

### Google Translator's Translation (1)
![aa_](https://user-images.githubusercontent.com/49169365/196082020-395f9b4d-c2b5-49af-9a31-e5aeace929c2.PNG)

### Wise Translator's Translation (2)
![d](https://user-images.githubusercontent.com/49169365/196082023-1f772c7a-5d8c-4434-aa3b-10adb589aa08.PNG)

### Google Translator's Translation (2)
![d_](https://user-images.githubusercontent.com/49169365/196082025-fe8c51cb-6cbc-46e3-9921-e0db6c51143d.PNG)

### Competitive translations between both translators
![Results](https://user-images.githubusercontent.com/49169365/196082027-0f98d913-803d-4dc4-8a53-ac2ab6a350d8.PNG)

