# Movie-Genre-Prediction-Model-Using-Neural-Network
# Introduction:
Movies, TV shows and Web Series are the greatest forms of entertainment in today’s era but not everyone has the same taste in terms of genres which they like. Ten years ago, it was very difficult to classify the movie genre but with the help of advanced techniques of ‘Deep Learning’ now it seems very easy. The idea of this project was to classify the user input into one or more movie genres and then suggest few movies based on those genres. This project explores the possibility of using Deep Neural Networks, NLP and HAN to classify the keywords as per genre using the movie summary plots and then provide the user with movie names which belong to that genre. Two models were compared in order to testify the working of this project. This module will be useful in saving users time and effort while searching for a specific movie and Deep Learning makes this process convenient and hassle free. 

# Data Description and Preparation:
The dataset is taken from 'CMU Movie Summary Corpus’ which has links to a dataset of movie plot summaries and associated metadata. The data is merged to create a combined and cleaned dataset with 4 to 5 columns which involve Movie id, Movie Name, Genre and Plot. The dataset consists of 363 different genres, which is then shortened down to 10 major genres. Finally, the dataset is of 36050 rows of movie names which are classified in 10 genres. 

#Model Description:
Two approaches were used for this project, one was the Basic model with LSTM attention mechanism and the second was Hierarchical Attention Network. HANs consist of stacked recurrent neural networks on word level followed by an attention model to extract important to the classification of the sentence and aggregate the representation of those informative words to form a sentence vector. It includes two levels of attention mechanisms — one at the word level and Multi-Label Movie Genre Classification from Plot Summaries, one at the sentence level — that let the model pay more or less attention to individual words and sentences when constructing the representation of the document. The plot summary serves as a keyword supplier and when a user enters a plot genre is predicted and movies are suggested accordingly.
