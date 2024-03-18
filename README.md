### Using Machine Learning Analysis to Detect Spam Messages

By Wilson Cheng

#### Executive summary

In this Capstone project, I explored the application of machine learning (ML) analysis to enhance spam filtering systems by effectively distinguishing between spam and non-spam (ham) messages. Leveraging advanced algorithms, my goal was to improve accuracy and efficiency compared to traditional filtering methods.

#### Rationale
The significance of this project lay in addressing the ongoing challenge of spam across various communication platforms. As digital communication continues to be a primary mode of interaction, the proliferation of spam poses threats ranging from privacy invasion to phishing attacks. An ML-based approach had the potential to significantly enhance the efficacy of spam filtering systems, reducing the risk of users encountering malicious content and improving overall cybersecurity.

#### Research Question
Could ML analysis effectively distinguish between spam and ham messages to enhance spam filtering systems?

#### Data Sources
I utilized a diverse dataset containing over 5,000 spam and ham messages, curated by the public domain and available for reference on [Kaggle](https://www.kaggle.com/code/abdallahwagih/spam-emails-detection-using-naive-bayes) (also uploaded to my [GitHub](https://github.com/Wilson-CK/Capstone_Project/blob/main/spam.csv)). The dataset was carefully selected to encompass various characteristics and content types commonly found in real-world communication. This comprehensive dataset served as the foundation for training and evaluating my ML models.

#### Methodology
My approach entailed applying a suite of prominent ML algorithms to train and assess models on the curated dataset, including:
* Logistic Regression
* K-Nearest Neighbor
* Decision Trees
* Multinomial Naïve Bayes
* Support Vector Machine (SVM) Classifier
* Stochastic Gradient Descent (SGD) Classifier
* Ridge Classifier

Cross-validation techniques were employed for robust evaluation, and hyperparameter tuning was conducted to optimize model performance. The process aimed to identify patterns and features indicative of spam messages, enhancing the models' ability to accurately classify messages.

#### Results
My research findings indicated promising results in the effective distinction between spam and ham messages. ML models showcased notable improvements in accuracy and efficiency compared to traditional spam filtering systems. The high F1 score, which combines precision and recall, highlighted how well the models dealt with two critical aspects of spam detection: false alarms and missed threats.
In simpler terms, it showed how accurately the models identified spam while also ensuring they didn't overlook important messages or wrongly label them as spam. This balance is crucial for maintaining trust in the filtering system and ensuring that legitimate business communications aren't mistakenly flagged as spam.
The **Ridge Classifier** model emerged as the clear winner, attaining nearly perfect results with 99.9% train accuracy and 98.1% test accuracy. It also showcased a low false positive rate of only 0.01%, demonstrating robust performance without succumbing to overfitting (where the model becomes overly tailored to the training data and performs poorly on new, unseen data).

#### Next steps
1. Refine the codebase for enhanced clarity and ensure the project's presentation caters to both technical and non-technical audiences.
2. Implement the ML models into existing spam filtering systems for real-world testing and validation.
3. Continuously update and retrain models with new data to adapt to evolving spam patterns.
4. Explore additional ML algorithms, deep neural networks, and ensemble techniques to further refine and improve spam detection capabilities.
5. Collaborate with cybersecurity experts to assess the models' real-world effectiveness against emerging threats.

#### Outline of project

Link to Jupyter Notebook: https://github.com/Wilson-CK/Capstone_Project/blob/main/Capstone_Project.ipynb

##### Contact and Further Information

Name: Wilson Cheng

For more information, visit my Capstone project page on GitHub:
https://github.com/Wilson-CK/Capstone_Project/
