# Summer-Project

News Sources:
1. Business Today
2. Indian Express
3. India Today
4. Times of India
5. Hindustan Times
6. The Hindu

Categories:
1. Education
2. Entertainment
3. Cities
4. LifeStyle
5. Business/Economics/Finanace
6. Sports
7. Technology
8. World

Types of file in each Category:
1. Each Category has some news sources and script to retrieve data. E.g. The_Hindu_Business.ipynb
2. "Combine_csv.ipynb" combines all the datasets of different news source in a particular category.
3. "tf-idf"/"Categorize.ipynb" consists of code to tokenize & stem the textual data to be used for further analysis of data. 2nd part to this is to remove similar articles/repeating articles using k means clustering after vectorizing texts with tf-idf. And at the end, outputs the csv to "Output CSV" folder.


Algorithmes Used:
1. tokenize and stem : tokenizes/stems the text words 
2. tf-idf : This weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus.
3. Cosine-Similarity: Calculates similarity between two documents.
4. K-Means Clustering: Cluster similar documents into 1 group


Purpose of the project : Make the daily news data ready for further analysis and to create a prediction model using Articles and there categories.


