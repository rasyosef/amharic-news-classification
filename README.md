# Amharic News Classification
This project implements a Deep Neural Network that uses the amharic news dataset from 
<a href="https://github.com/IsraelAbebe/An-Amharic-News-Text-classification-Dataset" target="_blank">here</a> 
and a word2vec Amharic word embedding from 
<a href="https://github.com/leobitz/amharic_word_embeddings" target="_blank">here</a>
to classify Amharic language news articles into 4 categories ('Business', 'International News', 'Politics', and 'Sport') with an **accuracy** of **88%** 
and an **f1-score** of **0.87**.

## Code
The `AmharicNewsTextClassification.ipynb` Jupyter Notebook contains python code for the entire process from loading and cleaning 
the data upto training the model. 

## Result
### Classification Report
![classification_report](https://user-images.githubusercontent.com/37704356/215358485-b16e11c0-e921-4537-9e4d-019c5674f4ed.png)

### Confusion Matrix
![confusion_matrix](https://user-images.githubusercontent.com/37704356/215540892-6650d73e-6452-45c8-b28d-1ce90bc12eef.png)


