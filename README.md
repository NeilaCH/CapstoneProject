# Udacity Capstone Project
## _Udacity Nanodegree Program_
The project is for the [Data Scientist Udacity Nanodegree program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
### _Table of Contents_
  1. Project Motivation
  2. Before Running the project
  3. Dataset Description
  4. Results
  5. License
## 1. Project Motivation
The problem that I chose to solve in this project focused on predicting student performance based on their intercation behavior in e-learning platform.
## 2. Before running the project
Before running the project you must have the following pakacges:
- Python 3.7
## 3. Dataset Description
The data is contained in a single file: education dataset - containing 480 student records and 16 features. 
The features are classified into three major categories: 
1. Demographic features such as gender and nationality. 
2. Academic background features such as educational stage, grade Level and section.
3. Behavioral features such as raised hand on class, opening resources, answering survey by parents, and school satisfaction.

TThe dataset is available in [Kaggle](https://www.kaggle.com/aljarah/xAPI-Edu-Data). According to [Abu Amrieh et al. (2016)](http://article.nadiapub.com/IJDTA/vol9_no8/13.pdf) the data is collected using a learner activity tracker tool, which called experience API (xAPI). The xAPI is a component of the training and learning architecture (TLA) that enables to monitor learning progress and learner’s actions like reading an article or watching a training video. The experience API helps the learning activity providers to determine the learner, activity and objects that describe a learning experience.
## 4. Results
The results pointed out that the use of features related to student profile, academic performance, and behavior with the virtual learning environment may lead to an accurate prediction of students performance while interacting with learning content. 
The classification results revealed that Random Forest outperformed other classifiers for both datasets
with an accuracy of 81%. With the set of selected features, the results highlighted that Random Forest classifier would rank a randomly selected student and predict their performance based on their academic and behavioral interaction with the learning platform.
Further improvements are required including:
1. The application of Gridsearch to find the optimal values for the classification model.
2. Including further classification techniques in the comarative phase
3. Explore features correlation to enhance the accuracy of the prediction model.
Building student model will further support implementing recommendation strategies to (a) support the cognitive development of students, (b) detect their interaction behavior, (c) determine their preferences, and (d) empower their learning performance. Thus, in future work, I will consider examine the task of recommending activities to have a better understanding of the impact of interaction behavior  on student performance in e-learning environment.


For more findings please check this [blog](https://chettaoui-neila.medium.com/udacity-starbucks-capstone-project-68f5127e29a9)
### License
1. The dataset extracted from [Kaggle](https://www.kaggle.com/aljarah/xAPI-Edu-Data)
2. Thank you Udacity for supporting the knowledge building
3. Amrieh, E. A., Hamtini, T., & Aljarah, I. (2016). Mining Educational Data to Predict Student’s academic Performance using Ensemble Methods. International Journal of Database Theory and Application, 9(8), 119-136.
