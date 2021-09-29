# Spam-Classifier-using-NLP
Implementing NLP concepts on the SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research.
 
Data taken from UCI site https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection
![image](https://user-images.githubusercontent.com/59803099/135151000-1937480a-eb6a-41dc-be3c-1599559f777d.png)

Data Set Information

Dataset contain following data with two columns Message and Label (Ham/Spam)
![image](https://user-images.githubusercontent.com/59803099/135191004-b280d6d7-541b-47dc-b19e-b1a2436363dc.png)


Performed following steps for Spam Classifier
1. Data Cleaning and  Preprocessing - Used NLTK libraries for removing stop words, Lemmetization, regular expression from the sentences
2. Created Bag of Words Model - Converted sentences into document matrix using countvectorizer having 5000 words
![image](https://user-images.githubusercontent.com/59803099/135191470-81f96aa1-f99f-4071-af66-3802288aa5c9.png)
3. Train Test Split - Test size of 30%
4. Trained model Naive Bayes Classifier which is good for NLP classifier
5. Accuracy of the model is 97%
![image](https://user-images.githubusercontent.com/59803099/135191403-cf887047-8a33-492a-9be3-2f1644388b23.png)



