# Resume_Screening_Process


It is the process by which a firm or institute decides a given candidate is suitable for the given position or not. It is often the first step in the proces of hiring individuals in the firm. Since the screeening is the first and thus, considered one of the important process in hiring people in the company, our model will help towards the smooth and hasselfree hiring of the employees. Also, when the company employees the ones with best skill set and talent, it will able to maximize its productivity and thus, helps in achieving the business objective of maximum profits.

![image](https://user-images.githubusercontent.com/82542269/189987189-783efeb9-2508-406c-bfe7-8bd3da14f24c.png)


## Data Exploration:


### Top 5  and Bottom 5 Categories of Job

![image](https://user-images.githubusercontent.com/82542269/189987778-5ba6b8ee-61d4-4820-bdca-60b1083770d2.png)


![image](https://user-images.githubusercontent.com/82542269/189987803-f5baa8ec-8d20-4b43-a933-716a14ab21ed.png)




### Wordcloud:

![image](https://user-images.githubusercontent.com/82542269/189987305-03168725-4e97-4a76-ab5a-553c9ead1ca5.png)

In our dataset, we have most categories with a developer , testing, engineer.


# Conclusion :


In this notebook, we started with a basic or general exploration of the dataset such as frequency of each category. Since the algorithm works with numerical data only, we used word embedding techniques to derive a numerical vector out of the text. 




We started with bag of words technique which gives use one-hot type vector based on the occurence of a word in a sentence. It gave us an accuracy of 92 percent using Support Vector Machine algorithm. In order to improve it, we applied a higher and better technique of word embedding , that is tf_idf vectorizer. It was able to improve our accuracy by 7 percent and gave a total accuract of 99 percent. This implies that each 99 out of 100 sample resumes were correctly predicted by the model.



###  References:

sklearn package: https://scikit-learn.org/

nltk  :https://www.nltk.org/

Regex: https://docs.python.org/3/howto/regex.html#regex-howto


