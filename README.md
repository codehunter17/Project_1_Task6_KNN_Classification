
# ✅ Task 6: K-Nearest Neighbors (KNN) Classification

### 👨‍💻 Done By: Krishna

---

## 📝 Objective:
The main objective of this task was to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for solving classification problems using Python.

---

## 📂 Dataset Used:
- **Dataset Name:** Iris Dataset  
- **Source:** Provided as `Iris.csv` file  
- **Features:**
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target Variable:** Iris Species (Setosa, Versicolor, Virginica)

---

## 🔎 Tools and Libraries Used:
- Python (Google Colab)
- Scikit-learn
- Pandas
- Matplotlib
- NumPy

---

## ✅ Stepwise Work Done:

### 1. Data Upload and Loading:
- Uploaded the **`Iris.csv` file** using Google Colab’s file upload feature.
- Loaded the dataset into a Pandas DataFrame.

### 2. Data Preprocessing:
- Dropped unnecessary columns like `Id` (if present).
- Converted the target column (Species) into numerical values using **Label Encoding**.
- Normalized the feature columns using **StandardScaler** to bring all features onto the same scale.

### 3. Splitting Data:
- Split the dataset into **training (70%)** and **testing (30%)** using `train_test_split` from Scikit-learn.

### 4. Model Training (KNN Classifier):
- Used **`KNeighborsClassifier` from Scikit-learn**.
- Started with **K=3 (number of neighbors)**.
- Trained the model on the training data.

### 5. Model Testing and Evaluation:
- Made predictions on the test set.
- Evaluated the model using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report (Precision, Recall, F1-score)**

### 6. Experimentation with Different K Values:
- Ran the model for **K values ranging from 1 to 10**.
- Calculated error rate for each K.
- Plotted a graph of **"Error Rate vs. K Value"** to identify the optimal K.

### 7. Visualizing Decision Boundaries:
- Selected **only 2 features (for visualization purposes)** from the dataset.
- Plotted **decision boundaries** to visually see how KNN classifies different species in 2D space.

---

## 📈 Screenshots / Graphs Generated:
- Error Rate vs. K Value plot
- Decision Boundary plot for KNN classification (using 2 features)

---

## ✅ Challenges Faced & Learning Outcomes:
- Faced a small issue with **file not found error** in Colab, but resolved it by learning how to **upload CSV files manually** and **read them using Colab upload code**.
- Learned the importance of **normalizing features** in distance-based algorithms like KNN.
- Understood how **K value affects model performance**.
- Got practical experience in **visualizing decision boundaries** in classification problems.

---

## 💡 Reflection:
This task helped me strengthen my understanding of **KNN algorithm** and how **hyperparameters like K** can directly impact classification accuracy.  
I also practiced **clean code structuring**, **self-debugging**, and **clear explanation of steps** which will help me in future interviews and hackathons.

---

## 🛠 Folder Structure for GitHub Submission:

