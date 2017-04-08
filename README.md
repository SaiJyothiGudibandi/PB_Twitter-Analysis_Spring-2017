# PB_Twitter Analysis_Spring-2017

Phase1:

Main Requirements:

• Collect tweets in JavaScript Object Notation (JSON) format (at least 100K record).

• Find the list of top ten used hashtags in your collection. 

• Create a directory in HDFS for each hashtag from the top ten hashtag list.

• Create additional two directories: “Others” and “None”, Store the tweets on files in HDFS
 If a tweet contains a hashtag from the top ten list, store the tweet in that hashtag’s directory. 
 If a tweet contains one or more hashtags, but none of the hashtags are in the top ten list, store the tweet in the “Others” directory.
 If a tweet does not contain a hashtag, store it in the “None” directory.

Extra Requirement:

• Implement a function that counts the number of times a keyword appears in one of two tweet JSON attributes (text and hashtags) in all of 12 directories that were created on HDFS: i nt count Word (String keyword, String attr) 

PPT:
https://github.com/saijyothi9/PB_Twitter-Analysis_Spring-2017/blob/master/Documentation/Principles%20of%20Big%20Data%20Project-Team14.pdf

Phase2:

Main Requirements:

Using the collection of tweets from Project 1 (or collect a new set), implement MapReduce programs to determine the vocabulary uniqueness of your dataset:

• M/R: Find the list of words that have duplicates in the tweets’ text.

• M/R: Find the list of words that are unique in the tweets’ text.

• Store the lists in two text files: dups.txt and uniqs.txt

• Print the ratio of the number of unique words to the number of words with duplicates.  

Extra Requirement:

Implement a MapReduce program to determine the best time to post a tweet.

• Propose the metric/criterion of your choice based on the tweet JSON format. 

• Run your program and return the top ten best times to post a tweet on twitter. 

PPT:
https://github.com/saijyothi9/PB_Twitter-Analysis_Spring-2017/blob/master/Phase2/Documentation/PB_phase2.pdf
