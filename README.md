# Quora question pair similarity

# Description 

###### Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.
###### Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

# Problem Statement
  * Identify which questions asked on Quora are duplicates of questions that have already been asked.
  * Tasked with predicting whether a pair of questions are duplicates or not.
  
# Sources/Useful Links
  #### Source : https://www.kaggle.com/c/quora-question-pairs

# Type of Machine Leaning Problem
  ##### It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.
  
# Performance Metric(s)
 * log-loss : https://www.kaggle.com/wiki/LogarithmicLoss
 * Binary Confusion Matrix
 
# Train and Test Construction
  ##### We build train and test by randomly splitting in the ratio of 70:30 or 80:20 whatever we choose as we have sufficient points to work with.
