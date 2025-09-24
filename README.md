🧮 MNIST Classification with Machine Learning

This project explores classical Machine Learning techniques to classify handwritten digits from the MNIST dataset.

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0–9), each of size 28x28 pixels.

📂 Project Structure
MNIST-Digit_Recognition/
│-- notebooks/
│   └── MNIST_classification.ipynb   # Main notebook
│-- README.md
│-- requirements.txt

⚙️ Installation

Clone the repository and install dependencies:

git clone https://github.com/<essskevin>/<MNIST_Digit_Recognition>.git
cd <MNIST_Digit_Recognition>
pip install -r requirements.txt

📊 Approach

Unlike Deep Learning, this project uses classical ML methods only.

1. Preprocessing

- Standardize pixel values

- Optionally apply Data Augmentation

2. Models Evaluated

- Logistic Regression

- k-Nearest Neighbors (k-NN)

- Random Forest Classifier

3. Model Fine-Tuning

- k-NN Fine-Tuning with RandomizedSearchCV

📈 Results (with Cross-Validation)
Logistic Regression	~91%
k-NN ~94%
Random Forest	~97%
k-NN (Fine-Tuned) ~96%
k-NN (Fine-Tuned + Data Augmentation) ~97%

📊 Evaluation

- Accuracy as metric

- Confusion Matrix to analyze per-class performance

- Visualization of misclassified examples


🚀 Future Work

- Compare with deep learning baseline (simple CNN)

- Implement PCA


📝 Main libraries:

- scikit-learn

- numpy

- matplotlib

- seaborn