# DATA 303 Final Project

For this Natural Language Processing project, I incorporated the fundamentals of NLP to create, compare, and contrast different machine learning models that take in user texts and accurately classify the type of emotion they convey.

## Description

Mental Health has always been an essential topic of discussion across various sectors of society today. Although modern advancements have assisted us in becoming more efficient in completing daily tasks, improving our physical health, and optimizing leisure time, many of the population's mental wellness remains a nationwide issue. According to studies, mental illnesses are currently affecting nearly a quarter of the overall United States population, with 1 in 10 adults experiencing mental health crises and over half of adults lacking mental care treatment. The main objective of this project is to integrate Natural Language Processing techniques to improve mental health care. Specifically, I am exploring statistical and machine learning models to perform sentiment analysis on user input. The reason why I am choosing to organize the project in this manner is because mental health is a vulnerable topic, and I want to investigate the best model that can assist people who are suffering from a mental illness. 

First, I obtained my dataset from Kaggle, an online data science platform with a wide selection of real-world datasets that can be used to perform data science tasks. This dataset consists of text sentences from various users with corresponding emotions. Moreover, the text data is already pre-organized in a .txt format, with testing, training, and validation files; this makes it convenient for me to use Python code to read and import them into my jupyter notebook. After that, I used numpy to create a data frame to store the data for further analysis efficiently. 

Due to the time constraints and the complexity of building various models, I narrowed my model selections to a few distinct statistical models, such as Linear Regression, Decision Tree Classifier, Support Vector Machine, and a neural network model, the Long short-term memory model. The reason why I specifically chose these models is that I aim to make comparisons between established models and models that I can create and tune their parameters; Python's built-in models, such as the linear regression, decision tree classifier, and SVM models, are all capable of conducting classification and regression tasks, while LSTM is a more complex supervised learning model that has a set of training sequences. It also solves the issue of vanishing gradients, a common phenomenon in deep neural networks that causes difficulty updating weights during training. With these models, I hope to find the best model for text classification and sentiment analysis. 

The results showed that a complex machine-learning model does not necessarily produce the most accurate results. The LSTM did not outperform the other models; the accuracy score was way lower than the different statistical models, averaging 35% accuracy. An inference I can make as to why the accuracy score is so low for the LSTM model is due to its hyperparameters and the time I spent on the experimental training aspect of this model. I believe I can further optimize the LSTM model's performance by constantly adjusting and testing the hyperparameters. 

Furthermore, the best model is the logistic regression model, with an accuracy score of 86.9%, followed by the Support Vector model, 86.7%, and the Decision tree, 86.15%. The LSTM model had the lowest overall accuracy score of 35%, proving that a neural network model may not outperform standard statistical models in Python. Although further work needs to be done to improve the performance of the classification models, throughout this project, I have developed a better understanding of applying different data science concepts to solve real-world problems. I learned that time, computational complexity, and code readability are the three most important topics to consider in this project. For instance, computational complexity impacts the amount of time for the models to run successfully and improve their quality. Code readability is another important thing to consider as it is easy to get lost in the construction of this notebook by not being able to understand where to edit code to optimize the model’s performances. In future studies, I plan on expanding this work to incorporate more advanced topics in data science to better support individuals in the mental health community. 

## Getting Started

### Dependencies

- Linux command line
- Project Jupyter
- Any other Python IDE (Integrated Development Environment)

### Installing

Please ensure that you have Project Jupyter downloaded to run the .ipynb file 

### Executing program

Open the terminal in your device and run jupyter lab - this will open up the jupyter notebook platform on your browser
Next import the .ipynb file to begin running the project! 

## Author

Contact info: 

Sophia Chen 

sophxchen@gmail.com

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
