# Prediction Of C-Section in a Pregnant Woman
This research project proposes machine learning based methods that could predict whether c-section method of child birth is suitable for a particular woman, taking note of all the pre-delivery features associated with a women's body.


## Abstract
The safety of the mother and the child largely depends on predicting the correct mode of delivery. Prediction is based on the opinion of the physician in charge of the delivery. If a wrong method is chosen, it could pose a great risk to the health of both the mother and the infant. Nowadays, many expecting mothers go for caesarean delivery without knowing whether it is suitable for them or not. In many developing countries, childbirth complications are a major delivery issue [1]. This study is divided into two parts: to identify the possible features used for determining the mode of childbirth and exploring and applying various machine learning algorithms on the best possible features predicting the mode of childbirth. To attain the objective, five different machine learning algorithms (KNN, Random Forest, Decision Tree, SVM, AdaBoost) have been applied. The dataset used for this research includes data of 4 different hospitals of Spain and contains a total of 6157 birth records and 161 features. 

Keywords:  Childbirth, Vaginal, Caesarean delivery, Supervised Machine Learning, Ensemble methods, AdaBoost, Random Forest, Decision Tree, SVM, KNN, SMOTE
## Introduction
Mode of delivery these days is one amongst the foremost relevant issues that worry gynaecologists, mental health authorities and mothers. At the end of pregnancy, a baby leaves the womb of a mother either through the normal delivery, also called the vaginal delivery which is the ancient method of delivery, not involving any medical tools or through c-section delivery, which is the modern technology involving childbirth through surgical methods[3]. Vaginal delivery is thought-about the most popular technique of delivery involving lower morbidity and mortality rates that c section. C-section delivers the baby through an incision made in the womb of the mother[2]. Both of these well-known deliveries have their own pros and cons and it may happen that the mode of delivery chosen for a particular woman might not suit the characteristics of that woman. This is happening in many developing countries such as Bangladesh, where the incorrect mode of delivery in the case of a woman causes temporary or permanent complications in her body. Incorrect methods of delivery pose various risks such as fatal termination, internal bleeding and respiratory issues in the baby in some cases.
C-section is performed often when a mother faces some complications in her delivery. This method is preferred in order to protect the health of the baby when normal delivery poses risks in the mother or the child. C-section helps in the cases when the labour stops or is very slow and not progressing, the baby is very large, the baby is in a breech position or the baby isn’t able to get enough oxygen[4]. A lot of times a mother's health is taken into consideration while choosing the mode of delivery. If a mother has an infection like HIV or genital herpes, then C-section is chosen as vaginal delivery could transfer the infection to the baby[4]. A mother having high blood pressure or diabetes can have difficult normal delivery, therefore c-section is preferred in such cases. Normal delivery in these cases can damage the organs and cause other problems.
World right now is going through lots of developments in various fields. AI has taken over the majority of sectors. In such conditions, C-section, being the modern technology and regarded as a less painful procedure is widely pursued for. Many countries with less developed medical sectors are pushing their people towards c-section, not knowing that c-sections create loads of complications to both the mother and the kid. In Bangladesh itself, the rate of avertible c section rate increased by 51% throughout 2016-2017 and 77% of all the c-sections in 2018 were medically unnecessary. During 2017 in Bangladesh, the maternal death rate was 173 over 100000 live births, which was higher than most of the developed countries. The same year, the United States saw 17 deaths per 100000 live births[3].Also, according to the Institute of Public Health Nutrition’s National Low Birth Weight Survey Bangladesh, in 2015, the caesarean section rate was 35% that exceeded the WHO’s suggested range of 10–15%. Compared to normal delivery, maternal mortality and morbidity saw an increase to approximately twice the rate for c-section delivery[3].
Generally, the selection of the mode of delivery is that of the medical skilled in charge. A maternal aid app will assist the doctors in predicting the mode of delivery and facilitate in reducing the complications of childbirth. A lot of studies have been conducted in order to predict pregnancy results. Some of the clinical decision support systems have also been developed. The research work already done involved developing a personalized prediction tool for normal birth after going through caesarean delivery using different ML algorithms. One such work included designing data mining classification models in order to predict modes of delivery using the factors associated with obstetric risk in real time.  Other studies on this research are introduced in the later sections of this report. However, there is a need for further research to predict whether the characteristics of a particular will be suitable for a particular mode of delivery and which algorithms will provide best accuracy for predicting the c-section probability in a mother[6]. Therefore, this research has been conducted keeping certain objectives in mind:
1.	Prioritizing features that are most important in predicting mode of childbirth
2.	Exploring the machine learning algorithms to check which model will give best accuracy in the predictions. 
## Literature Review
A systematic and detailed literature review was carried out for this research project. Muhammad Nazrul Islam, et. al [3] conducted a study to find best machine learning algorithms to predict the mode of childbirth. They used algorithms such as Decision tree, random forest, KNN and SVM to predict the modes of childbirth. The accuracy of all the models ranged from 74% to 97% when applying the models on different features of low importance to high importance. The outcome showed the accuracy of all the applied models and the important factors that determine the mode of childbirth. It classified the factors into various categories from less important to most important. However, the research carried out was not easily understandable. It opened the door to many types of deliveries and the terms used are less known to people and more to medical practitioners.
Campillo-Artero et al[5]. did a study in order to determine the factors leading to emergency c-section  using the ML classification Algorithms- Logistic regression, Classification tree and Random forest. The accuracy of the models in this research ranged from 74% to 81%. The result of this research focused on the mothers who were older than 35 and had higher body mass index and were more likely to have gone through c-section before.
S.A. Abbas et al.[6] did research to relate the probability of c-section with the age of the mother. The result of the study concluded that the mothers who were younger than 20 years and those who were older than 35 years have higher probability of going forward with c-section. The study also concluded that those women who go through c-section have higher blood pressure than those with normal deliveries[3].
Research by Md. Sakib Bin Alamet et al.[1] focused on the bagging ensemble classifiers. The study concluded that the bagging ensemble classifiers had performed better than the traditional machine learning algorithms in the domain of predicting childbirth.
Nafiz Imtiaz Khan et al.[7] conducted another study in which they used supervised ensemble machine learning models: Adaboost, Cat Boost and XGBoost. This study did not show very good accuracy results as only 11 features were considered in order to predict the c-section delivery.
Jeong Ha Wie et al.[8] did the study on prediction of emergency c-section using machine learning algorithms. Among the nine machine learning models used, logistic regression had the best performance. The study concluded that the pre-gestational maternal weight was associated with the c-section, whereas maternal weight at the time of delivery did not affect the prediction. It also concluded that the risk of c-section increased with increase in neonatal birth weight. The study also showed some limitations. The main limitation was that the study was a retrospective cohort study. 
Mona M. Jambool[9] conducted research on data mining in health care to predict caesarean delivery operations. It resulted in the conclusion that naive Bayes approach outperformed all the other models used. The results were realistic due to the CV approach used while evaluating the performance of the classifier.
Thus, to summarize, a lot of concerns were observed throughout the literature review. Quite a number of studies focused on the prediction of c-section using different types of traditional ML algorithms, while some tried to find relation between various features of a woman and chances of c-section regarding those features and some tried to find out the best features that are most important for determining the mode of childbirth. Therefore, keeping in mind the literature review, this study focuses on the prediction of caesarean section in a pregnant woman using specific machine learning algorithms as well as ensemble machine learning techniques to achieve a better accuracy.
## Proposed Methodology
The research work to build the proposed model has been carried out in four phases namely Data Collection, Data Pre-processing, Training the model and Performance analysis of the model. The above Phases have been briefly described in the following subsections. The pictorial representation of the proposed model is shown in Fig 1. 
![image](https://user-images.githubusercontent.com/74055483/199098176-d846e5d1-5861-4b96-9da7-1118e3a07805.png)
### Phase 1: Data Collection
The dataset used in this study was prepared by Campillo-Artero et al. [5], in order to build effective and efficient ML models. The dataset consists of birth records of four public hospitals of Spain in the year 2014. It consists of 6157 singleton birth records and a total of 161 features which includes 141 categorical and 19 numerical and 1 unnamed feature. The dataset also contained some columns which were unnamed and thus were removed from the dataset. It consists of some pre-delivery as well as post-delivery attributes which are useful in determining various predictions related to mother as well as child birth like, Amniotic Liquid, Oxytocin, Previous Caesarean, Age, Height, Weight, Foetal Intrapartum pH, Type of Birth etc. 
### Phase 2: Data Pre-processing
In this phase, collected data was synthesized. Duplicate data as well as noise were removed from the dataset. Null values were removed by applying different missing value imputation techniques like mean, median imputation for numerical features and frequent values as well as filling null values with a category called missing were performed. Machine Learning models can work upon numerical data only, due to this reason categorical encoding was performed. For this purpose, Label encoding which labels the categories into a numeric form was implemented. Since the objective of the study was to predict the C-section, therefore features which were irrelevant with the study were also removed. 32 important features among the left features were selected for the further analysis and model building purpose. The features used in the proposed model have been taken according to the reference paper [3].
The dataset collected consists of unbalanced data, grouped by type of birth. In Order to build the more effective and accurate classification Synthetic Minority Oversampling Technique (SMOTE) was implemented. This algorithm helps to overcome the imbalance data problem by synthetically generating the new instances using an interpolation method.
### Phase 3: Training the Model:
Under this phase different well-known machine learning algorithms were selected which includes Decision Tree (DT), K-Nearest Neighbour (KNN), Support Vector Machine (SVM) to train the model. Ensemble machine learning techniques like Adaboost and Random Forest have also been implemented to classify the subject i.e. type of birth into C-section or non-C-section. Ensemble methods are supervised ML techniques that combine the predictions of several base models so as to produce one optimal model for prediction. This gives a better predictive performance compared to implementing a single model. These models are implemented using Scikit Learn which is a python module integrated with a wide range of Machine Learning algorithms
### Phase IV: Performance Evaluation
Cross Validation technique is a statistical technique for performance evaluation of machine learning models. In this study Stratified K fold Cross Validation technique which works well for the imbalance dataset. In this the whole dataset is divided into k folds of equal size having the same ratio of instances of C-section and non-C-section. 
F1 score - F1-score is a measure of a model’s accuracy on a dataset. It is the way of combining precision and recall of a model and is the harmonic mean of the model’s precision and recall [13]. F1 score is a good choice for comparing different models predicting the same thing.
Precision - Precision of a model refers to the percentage of its results which are relevant [14]. It is the ratio of correctly classified positive examples to the total positively classified examples.
Recall - Recall of a model refers to the percentage of the total relevant results correctly classified by the algorithm [15]. It is the ratio of correctly classified positive examples to the total actual positive examples.
ROC-AUC - Receive operating characteristics curve (ROC) - Area under the curve (AUC) is the performance measure at various threshold settings for the classification problem. ROC is a probability curve on the other hand AUC is a measure of separability and the graph from true positive rate to false positive rate.
Performance of every prediction model is measured in terms of accuracy, precision, recall, F1 score and ROC-AUC curve. ROC-AUC score is used for the final model selection. Results are briefly described in the following subsections.
## Results
#### Decision Tree
 Decision Tree consider different hyperparameters like criterion for splitting (entropy and gini index) and number of folds (3, 5, 10) for stratified K fold cross validation folds. From the below table it can be seen that the highest F1 score obtained for the Decision Tree is 0.94218 when entropy is considered as criterion for splitting and 10 folds cross validation is considered. Highest ROC-AUC is 0.89232 is obtained when the combination of gini index as criterion and 5 folds is considered as hyperparameters for training the model.
#### Random Forest
Random Forest consider different hyperparameters like criterion for splitting (entropy and gini index), number of estimators (20, 30, 40, 50) and number of folds (3,5,10) for stratified K fold cross validation folds. From the below table it can be seen that the highest F1 score obtained for the Random Forest is 0.95355 when entropy as criterion, 50 estimators and 10 folds cross validation is considered. Highest ROC-AUC is 0.98513 is obtained when the combination of entropy as criterion, 50 estimators and 5 folds is considered as hyperparameters for training the model.
#### K Nearest Neighbor
KNN considers different hyperparameters like P (1 for Manhattan distance measure and 2 for Euclidean), number of neighbours (10, 15, 20, 25) and number of folds (3,5,10) for stratified K fold cross validation folds. From the below table it can be seen that the highest F1 score obtained for the KNN is 0.91278 when Manhattan as distance measure with 10 estimators and 10 folds cross validation is considered. Highest ROC-AUC is 0.96037 is obtained when the combination of Manhattan as distance measure with 25 neighbours and 5 folds is considered as hyperparameters for training the model. 
#### Support Vector Machine
SVM consider different hyperparameters like kernel (Linear, rbf, Polynomial) and number of folds (3,5,10) for stratified K fold cross validation folds. From the below table it can be seen that the highest F1 score obtained for the SVM is 0.94721 when the rbf kernel is used with 10 folds cross validation is considered. Highest ROC-AUC is 0.97358 is obtained when the combination of the rbf kernel and 10 folds is considered as hyperparameters for training the model 
#### Adaboost
Adaboost considers different hyperparameters like Decision Tree and Random Forest as base estimators, learning rate (0.01, 0.1, 1), number of estimators (20,30,40,50) and number of folds (3,5,10) for stratified K fold cross validation folds. From the below table it can be seen that the highest F1 score obtained for the Adaboost is 0.95322 when the Decision Tree as base estimators with 0.01 as learning rate and 30 estimators along with 10 folds cross validation is considered. Highest ROC-AUC is 0.98532 is obtained when Random Forest  is considered as base estimator along with the combination of 0.1 as learning rate, 30 as number of estimators and 10 folds is considered as hyperparameters for training the mo
## Conclusion
Selecting suitable modes of childbirth is important for the safety of mother as well as new born child. But the best set of features for predicting can be explored more. This study examined all possible features for classification of type of birth and different models were applied. In this report, we compared a variety of traditional classifiers like Decision tree, KNN, SVM with the ensemble classifiers like AdaBoost and Random Forest which are the novel techniques used in prediction of childbirth mode. It has helped the doctors as well as the user to identify key factors that influence caesarean section. In this research, performances of all the algorithms with different performance parameters like precision, recall, F1 score and ROC-AUC are shortlisted on the basis of ROC-AUC score of all the models with different parameters. The research concluded with the AdaBoost model having the highest ROC-AUC score i.e. 0.98532 when it is considered to train the data with Random Forest base estimator along with the combination of 0.1 as learning rate, 30 as number of estimators and 10 folds. The second highest score was obtained for Random Forest i.e. 0.98513. Thus, it is observed that ensemble machine learning models show a better performance than the traditional machine learning models.
![image](https://user-images.githubusercontent.com/74055483/199099855-f57f68d0-1806-48b9-927e-7869abe7c39d.png)
