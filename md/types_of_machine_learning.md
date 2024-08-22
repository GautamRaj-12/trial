# Types of Machine Learning

Machine learning can be categorized into several types based on how the algorithms learn and make predictions. The main types are:

## 1. Supervised Learning

- **Definition**: Algorithms learn from labeled training data to make predictions or decisions.
- **Characteristics**: Requires input-output pairs where the output is known. The goal is to predict the output for new, unseen data.
- **Examples**:
  - **Classification**: Assigns labels to input data (e.g., spam detection in emails).
  - **Regression**: Predicts continuous values (e.g., predicting house prices).

## 2. Unsupervised Learning

- **Definition**: Algorithms learn from unlabeled data to identify patterns and relationships.
- **Characteristics**: No labeled output; the system tries to learn the structure of the data on its own.
- **Examples**:
  - **Clustering**: Groups similar data points together (e.g., customer segmentation).
  - **Dimensionality Reduction**: Reduces the number of features while retaining important information (e.g., Principal Component Analysis - PCA).

## 3. Semi-Supervised Learning

- **Definition**: Combines a small amount of labeled data with a large amount of unlabeled data during training.
- **Characteristics**: Utilizes both labeled and unlabeled data to improve learning accuracy.
- **Examples**:
  - **Web Content Classification**: Using a few labeled examples to categorize a large amount of unlabeled web content.

## 4. Reinforcement Learning

- **Definition**: Algorithms learn by interacting with an environment to maximize cumulative rewards.
- **Characteristics**: Involves agents taking actions in an environment to achieve a goal. Feedback is provided in the form of rewards or penalties.
- **Examples**:
  - **Game Playing**: Training agents to play games like chess or Go.
  - **Robotics**: Teaching robots to perform tasks through trial and error.

## 5. Self-Supervised Learning

- **Definition**: A type of supervised learning where the system generates its own labels from the input data.
- **Characteristics**: Creates pseudo-labels or auxiliary tasks from the input data to learn representations.
- **Examples**:
  - **Natural Language Processing**: Predicting missing words in a sentence (e.g., BERT).

## 6. Transfer Learning

- **Definition**: Utilizes knowledge gained from one task to improve learning in a related but different task.
- **Characteristics**: Pre-trained models are adapted for new tasks with limited data.
- **Examples**:
  - **Image Classification**: Using a model trained on a large dataset like ImageNet and fine-tuning it for specific image recognition tasks.

# Classification vs Regression vs Clustering

| **Aspect**       | **Classification**                                 | **Regression**                                      | **Clustering**                                     |
|------------------|----------------------------------------------------|-----------------------------------------------------|----------------------------------------------------|
| **Definition**   | Predicts categorical labels based on input data.  | Predicts continuous values based on input data.    | Groups data points into clusters based on similarity. |
| **Output**       | Discrete labels or categories.                     | Continuous values.                                 | Groups or clusters.                                |
| **Goal**         | Assign input data to one of several predefined categories. | Estimate a numeric value based on input features. | Discover inherent groupings in data without predefined labels. |
| **Examples**     | - Email spam detection (spam or not spam)          | - Predicting house prices                           | - Customer segmentation (e.g., market segments)   |
|                  | - Disease diagnosis (disease or no disease)         | - Forecasting sales figures                         | - Document clustering (grouping similar documents) |
| **Evaluation Metrics** | - Accuracy<br>- Precision<br>- Recall<br>- F1 Score | - Mean Absolute Error (MAE)<br>- Mean Squared Error (MSE)<br>- R-squared | - Silhouette Score<br>- Davies-Bouldin Index<br>- Inertia |
| **Algorithms**   | - Logistic Regression<br>- Decision Trees<br>- Support Vector Machines (SVM)<br>- Naive Bayes | - Linear Regression<br>- Polynomial Regression<br>- Ridge/Lasso Regression | - K-Means<br>- Hierarchical Clustering<br>- DBSCAN |
| **Use Case**     | Suitable for tasks where the goal is to classify data into predefined categories. | Suitable for tasks where the goal is to predict a continuous outcome. | Suitable for tasks where the goal is to identify natural groupings in the data. |

