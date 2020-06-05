# Check-That-2020
This repository holds the work done for the Check That lab in the CLEF 2020 condference. It was submitted through SSN college of engineering witht the team ID as SSN_NLP 
## Task 1 : tweet check worthiness
 Given a topic and a stream of potentially-related tweets, rank the tweets according to their check-worthiness for the topic
 Tweet check-worthiness: A check-worthy tweet is a tweet that includes a claim that is of interest to a large audience (specially journalists), might have a harmful effect, etc.
 
 We preprcoessed the data by removing punctuations and stopwords, Lower-cased ,and lemmatized the text. Two runs were implemented  one was done using a convolutional neural network by feeding the text converted to vectors, second was done using the roberta transformer model.

Traditional machine learnign models like Naive Bayes and Supoort Vector Machines were also implemented. But neglected due to their unsatisfactory performance in relevance to this task
