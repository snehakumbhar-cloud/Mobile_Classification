# Mobile_Classification

This project uses machine learning classification algorithms to predict the *price range* of mobile phones based on their specifications. It demonstrates a full pipeline from data preprocessing to model evaluation using scikit-learn.

---

### 🔍 Dataset Overview
- Source: train.csv and test.csv from local directory
- Target variable: price_range (0 = low, 1 = medium, 2 = high, 3 = very high)
- Features include:
  - Battery power, RAM, internal memory
  - Camera specs (fc, pc), screen size (sc_h, sc_w)
  - Connectivity (blue, four_g, three_g, wifi)
  - Others: dual_sim, touch_screen, px_height, px_width, etc.

### 🧪 Models Used
- *Logistic Regression with Cross-Validation*
- *Gaussian Naive Bayes*
- *K-Nearest Neighbors (KNN)*

Each model was trained using train_test_split with random_state=42 for reproducibility.


### 📊 Evaluation Metrics
- *Confusion Matrix*
- *Accuracy Score*
- *Classification Report* (Precision, Recall, F1-score)


### ✅ Key Results
- KNN model achieved competitive accuracy on test data.
- Predictions were made on unseen test data (test.csv) after feature alignment.
- Class distribution of predictions was visualized using value_counts().


### 📁 Files Included
- mobile_prediction.ipynb: Jupyter notebook with full code
- train.csv, test.csv: Dataset files
- README.md: Project summary and instructions

### 🚀 How to Run
1. Clone the repo
2. Place train.csv and test.csv in the root directory
3. Run mobile_prediction.ipynb in Jupyter or Colab
4. View model performance and prediction outputs

