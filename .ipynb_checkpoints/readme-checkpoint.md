# Author Classification Project 
Using NLP and techniques of supervised learning (including Deep Learning) and unsupervised learning (emphasizing on unsupervised for this project), and collect thousand texts from Gutenberg project (and 7 novels) for at least 10 authors, build a project to classify text-author. 


The project should follow the guideline as: 

1. Pre-process data using Spacy and other methods. 
2. Perform data exploration 
3. Using Bag of Word, apply supervised models such as Naive Bayes, Logistic Regression, Decision Tree, Random Forest, KNN, SVM and Gradient Boosting, including GridSearchCV. 
4. Similar to 3., but using TF-IDF. 
5. Similar to 3., but using word2vec. 
6. Apply RNN to do classification. 
7. Using unsupervised technique, visualize bar graphs for clusters containing 10 author documents. Adjust by silhouette scores. 
8. Using LSA, LDA and NNMF, print out top ten words (with their highest loading) for each topic modeling. Analyze and compare among three methods. 
9. Write up analysis and conclusions.  


# serial_test.ipynb

I experienced a lot of snags during the data cleaning process. I had too many documents and was getting a lot of insufficient memory errors. 

I have created and saved serial_test.ipynb to display some of my decision making. This is to help answer any questions such as why I choose the number of documents that I've selected, etc. 

It's named serial_test because the process ended with which serialization method that I'm using to save the documents. 

# Note:

This notebook was run in interations. A system was set up such that I could create and run a model on the fly by accessing the pickled documents and then processing them if I happened to require a reboot of my machine. 

Because of the time constraints affiliated with the duration of the project - that is; I had a deadline, there are and may be some indescrepancies. Nuances such as not all feature engineered were searched with the same number of parameters. There may have been some updates to certain functions that did not get tested across the entire project.

It may also appear as though the project could use some combining. For example I have multiple functions labeled "model_data" with extensions within them prior to denote the different features that I'm using. This is a design flaw. Unfortunately, updating the functions to accomodate the enhancements associated with these featured analysis and will result in untest/non-tested data and could result in confusion as someone investigates the output. As such; I opted for more code over less. Such is the way of the world in a situation when more than just the output matters. If I was only concerned with the results and not the process that went behind those results; this project may have read a little cleaner. 

I have struggled with the layout of this project. It is entirely possible that the project would read better and easier as a series of notebooks stored in different files labeled as the specific feature process/standardization that I have chosen and having put the data cleaning in it's own folder as well. There are a number of options. Alas, I am also tasked with placing all information in one convenient page and therefore; it's rather long. 
