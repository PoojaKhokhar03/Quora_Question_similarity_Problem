# Quora_Question_similarity_Problem
##  Business Problem
#### Description
Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.




### Problem Statement

Identify which questions asked on Quora are duplicates of questions that have already been asked.
This could be useful to instantly provide answers to questions that have already been answered.
We are tasked with predicting whether a pair of questions are duplicates or not.

#### Real world/Business Objectives and Constraints
The cost of a mis-classification can be very high.
You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
No strict latency concerns.
Interpretability is partially important.


#### Data Overview
- Data will be in a file Train.csv
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
- Size of Train.csv - 60MB2.2.1 Type of Machine Leaning Problem
- Number of rows in Train.csv = 404,290


#### Type of Problem
It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.

### LSTM 
we will use LSTM to solve this problem,because LSTMs are very effective in sequence prediction problem, the reason they work so well is that they store past important information and forget the information that is not.

After modelling, then I predicted my data set. 

#### Conclusion
- Deep Learning is very slow.
- To create corpus of vectors was also very time consuming.
- we can add more features to improve model’s performance.
- We can try to add more layers ar any other model to improve the performance.




