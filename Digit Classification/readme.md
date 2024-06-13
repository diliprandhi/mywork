# Digit Classification

## Summary:
The Digit Classification project aims to develop a machine learning model to accurately classify handwritten digits from the MNIST dataset. Using a Support Vector Machine (SVM) algorithm, this project showcases the application of machine learning techniques to image recognition tasks, achieving high accuracy in digit classification.

## Detailed Description:
The project starts with loading and exploring the MNIST dataset, which consists of 60,000 training images and 10,000 test images, each representing a handwritten digit from 0 to 9.

**Key steps in the project include:**

**Data Preprocessing:**
- **Normalization:** Scaling pixel values to a range of 0 to 1 to improve the performance of the machine learning model.
- **Train-Test Split:** Dividing the dataset into training and test sets to evaluate the model’s performance.

**Model Building:**
- **Support Vector Machine (SVM):** Implementing an SVM classifier. SVM is chosen for its effectiveness in high-dimensional spaces and its robustness in terms of classification accuracy.
- **Training the Model:** Using the training data to train the SVM model. The training process involves finding the optimal hyperplane that separates different digit classes in the feature space.

**Model Evaluation:**
- **Accuracy:** Calculating the model’s accuracy on the test set to assess its performance.
- **Confusion Matrix:** Creating a confusion matrix to visualize the model’s performance in classifying each digit.
- **Precision, Recall, and F1-Score:** Computing these metrics to gain a deeper understanding of the model's performance.

**Visualization:**
- **Sample Predictions:** Visualizing a few samples of the handwritten digits along with their predicted labels to provide a qualitative sense of the model’s accuracy.
- **Confusion Matrix Visualization:** Using heatmaps to visualize the confusion matrix, making it easier to identify where the model is making errors.

### Technologies Used:

- Python (Pandas, NumPy)
- Scikit-learn for model building and evaluation
- Matplotlib and Seaborn for data visualization

### Usage:
Clone the repository, install the required libraries, and execute the script to train the model and classify handwritten digits.
