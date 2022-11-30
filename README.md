# CMSC-516-Information Extraction

Text mining frequently employs the technique of InformationExtraction. By analyzing the the text (in this case, a tweet), using sophisticated text mining techniques, it is possible to determine if it is location a name or a few other text categories.

# Installation Instructions <br/>
 1)Install Python on you Computer. <br/>
 2)Download Anaconda Navigator. <br/>
 3)Launch jupyter Notebook from Anaconda Navigator.<br/>
 4)Upload the "named-entity-recognition-ner-with-tensorflow (2).ipynb" in your Anaconda Navigator.<br/>
 5)upload the dataset downloaded from kaggle (you can find this in the data folder in this repository) into your Jupyter Notebook.<br/>
 6)Run the ipynb file on your Jupyter Notebook. <br/>
 
# Data <br/>
1)we used "ner_dataset.csv" dataset and has 4 features. . <br/>
2)These are the features in the dataset. <br/>
  Sentence #	Sentence	POS	Tag
 
# Method <br/>
1)Imported all the libraries like pandas, tensorflow, sklearn and nltk.<br/>
2)Loaded the Dataset using pandas. <br/>
3)We are mainly intrested in the target label, text, so we visualize and see the data. <br/>
4)We cleaned the data by removing stopwords,punctuations,repeating characters, url and numbers.<br/>
5)Then we tokenize the tweet text. <br/>
6)We split the dataset into 70% train and 15% test and 15% validation. and use the "target" label for testing. <br/>
7)We used TfidfVectorizer model for feature selection with a max feature limt. <br/>
8)There were a total features of 6100. <br/>
9)Then we used classifiers like naive bayes, Decision Tree, multiLayer Perceptron. <br/>

# Results <br/>
1)Results using sequential vs 97
  
# Discussion <br/>
Comparing the results from the three classifiers produced me a results of 
Sequential :- 97
![image](https://user-images.githubusercontent.com/46966138/196500511-40e4dd97-8bfd-48e5-9dcb-c7ade3037703.png)


# Future Work <br/>
I want to finish my implementation of Bert and word2vec with the same three classifiers and compare the results.
Try to use implement CNN.
![image](https://user-images.githubusercontent.com/46966138/196500616-83d25ad6-f248-4110-b256-d5b171ffe9a9.png)
