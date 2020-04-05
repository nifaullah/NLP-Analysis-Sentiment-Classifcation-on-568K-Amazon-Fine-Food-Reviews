#  NLP Analysis & Sentiment Classification on 568K+ Amazon Fine Food Reviews 


**Dataset:**

Amazon Fine Food Reviews dataset is downloaded from [Kaggle](https://https://www.kaggle.com/snap/amazon-fine-food-reviews) and placed in my google drive for programmatic retrieval. It consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~568,000. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories. You can read more about the data at [SNAP](https://snap.stanford.edu/data/web-FineFoods.html).

**Approach:**

Many a time in business, as well as in academia, we don't have the luxury of proper data pipelines to decide the scope and the value associated with data beforehand, and often we derive value out of already collected, sometimes good but often messy, data. That was the case for this analysis, and that is why you'd find the Goal of the project in section 3. 

An analysis is a sequential process, which involves a lot of questions back and forth. I've tried to capture this natural question and answer process by appropriately documenting the question and the answer to the question either through text or through python commands. 

I think this approach at least serves two purposes first it gives me an option to analyze my thinking, to see what kind of question I am asking and to track my approach to a problem. Secondly, some times when we read someone else's analysis we find it too hard to decipher some of their actions, this is an intuitive way where the question precedes an action, thereby self-explaining the action at each step. I've tried to keep the questions as natural as possible. 

Sometimes 4 or 5 questions into some section of the analysis you may feel I could've skipped questions 1, 2 & 3 and reached straight to questions 4 & 5 but when we do analysis it seldom happens that you reach straight to the goal, it is often preceded by some missteps or extra steps before where we eventually reach where we reach, and I am attempting to document those missteps and extra steps. 

I would love for you to read the analysis in its entirety, but it is possible that you may feel that the analysis is too lengthy and that you may not have enough time to go through the entire analysis. If that's case I would strongly suggest you atleast read the summary part( section 9.1). 

**Key Results:**

1. Model finalized was a RNN model (LSTM Cells).
2. Model had an initial train and validation accuracy of 90%.
3. Model had Sensitivity of 91.44%, Specificity of 93.56% and precision equal to 98.06%.
4. Upon detailed analysis of the errors, model accuracy and learning was found to be higher than the earlier assessment. 
5. Model is close to the desired Low Bias Low Variance sub-section.
6. Learned weights can be successfully used to learn sentiments for similar tasks in different problem areas through transfer learning.
7. RNN Architecture (including the LSTM cell) is extremely powerful at dealing with sequence learning problems, especially more so when it comes to Natural Language Processing.
