# Chatbot - Summer Internship Project 2019 


### Project description
A generalised chatbot which can intelligently respond to conversation using named entity recognition (NER), sentiment analysis and an implementation of a decision system for follow up mechanism using a Seq2seq model which uses Bidirectional RNNs and Attention models.

### Files
model.py is the main file and it contains the model as well as the retrieval based system

### Encoder-Decoder Model
<!--Add the image from the project report folder-->

<!--create an images folder and change to relative path later

### Decision System for Follow Up
<!--Insert the flow chart here-->


### Instructions

Create an IBM Cloud account. Follow the steps mentioned in the following link-
https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/get-started-wdp.html

Using the dialogflow api
https://cloud.google.com/dialogflow/docs/quickstart-api


### Installation
To run the chatbot program you must install the following libraries -
1. Install spacy 
``` deic
pip install spacy
```
2. Install tensorflow
```
pip install tensorflow
```
3. Install dialogflow
```
pip install dialogflow
```
4. Install textblob
```
pip install textblob
```
5. Install tqdm
```
pip install tqdm
```
6. Install tensorlayer
```
pip install tensorlayer
```
7. Install wikipedia
```
pip install wikipedia
```
8. Install Watson NLU
```
pip install ibm_watson
```
9. Install Spacy's English Model
```
python -m spacy download en_core_web_md
```
10. Install numpy
```
pip install numpy
```
11. Install pandas
```
pip install pandas
```
12. Install tensorlayer
```
pip install tensorlayer
```



### API's used -
1. MediaWiki
2. Dialogflow
3. IBM Watson NLU (for sentiment analysis)


### Training data
We have trained our model on three different datasets (SQuAD , Cornell Movie Dialogue Corpus and a Trump Tweets Dataset) to  bring about generalisation. They are included in the 'data' folder and are included through an import of the folder.


### Usage 
Note - First make sure that all the files required are saved in the same directory and all the required libraries are installed before running the program.
For Windows -

To run it on squad
```
python model.py squad
```
To run on cornell_corpus
```
python model.py cornell_corpus
```
To run on twitter
```
python model.py twitter
```

For Linux (For Python3+ versions) -

To run it on squad
```
python3 model.py squad
```
To run on cornell_corpus
```
python3 model.py cornell_corpus
```
To run on twitter
```
python3 model.py twitter
```

The model can be trained on the user's system or the pretrained weights (.hdf5 files) included in the respective folders can be loaded to view the output.

### Results
The results of the chatbot (including the follow up) are shown below -
<!--Insert a screenshot of the results here-->

### References
<!--Insert the links of all blogs and resources that helped our cause-->
-----------------------------------------------------------------------------------------------------------------------------------
 
