# AIE241: Natural Language Processing Project
## Automated Robust Feedback Analysis System for Departments and Teachers

### Objective
Develop an application for efficient feedback submission about departments and teachers.

### Key Features
1. **Feedback Input**: User-friendly interface for submitting feedback.
2. **Data Processing with NLTK**: Utilizes Natural Language Toolkit (NLTK) for advanced linguistic analysis of feedback.
3. **Sentiment Analysis**: Implements machine learning algorithms for sentiment analysis.
4. **Optimal Algorithm Selection**: Evaluates and selects the most effective algorithm for sentiment and subjectivity extraction.
5. **Feedback Classification**: Categorizes feedback into Positive, Negative, or Neutral.

### Goal
To provide comprehensive and objective feedback analysis, aiding educational decision-making through student insights.

## Core Features
- **Feedback Collection**: Collects student feedback on various academic aspects like teaching quality, course content, and facilities.
- **Advanced Data Processing**: Employs Natural Language Toolkit (NLTK) for data extraction and processing.
- **Sophisticated Sentiment Analysis Models**: Utilizes Multinomial Naive Bayes and Support Vector Machine (SVM) classifiers, both with and without text stemming, to gauge sentiments from the feedback.
- **Comprehensive Dashboard System**: Features a dashboard for administrators with overall sentiment statistics, and individual dashboards for department heads and faculty.

## System Architecture
- Implements feedback preprocessing and sentiment classification into positive, negative, and neutral categories.
- Incorporates role-based user authentication for administrators, heads of departments, and faculty members.

## Enhanced Machine Learning Approach
The system's architecture incorporates a comprehensive approach that includes data collection, model development, and evaluation, focusing on the following machine learning models:

- **Multinomial Naive Bayes Classifier**: A probabilistic model suitable for text classification that considers the frequency of words.
- **Support Vector Machine (SVM) Classifier**: A robust classifier that finds the optimal hyperplane for class separation.
- **Multinomial Naive Bayes Classifier with Stemming**: This variation incorporates stemming to reduce words to their root forms, potentially improving classification accuracy.
- **Support Vector Machine (SVM) Classifier with Stemming**: Combining SVM with stemming to enhance the model's ability to generalize from the training data.

## Conclusion
The project successfully achieves its goal of streamlining feedback collection and analysis, providing valuable insights for academic improvement.
