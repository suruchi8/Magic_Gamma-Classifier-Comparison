# MAGIC Gamma Telescope Classification – Model Comparison

This project compares multiple supervised machine learning models on the **MAGIC Gamma Telescope dataset**.  

### Dataset:
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

Donated by:
P. Savicky
Institute of Computer Science, AS of CR
Czech Republic
savicky '@' cs.cas.cz

## 🧠 Models Implemented
The following algorithms are trained and evaluated:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Naive Bayes**
- **Neural Network (TensorFlow / Keras)**
  
## 🛠️ Workflow
1. **Data Preprocessing** – class conversion, feature scaling
2. **Exploratory Data Analysis** – visualization of feature distributions
3. **Train/Validation/Test Split** – 60/20/20
4. **Model Training** – each model trained on the same dataset
5. **Evaluation** – confusion matrix, classification report, and accuracy comparison

## 📈 Results
The notebook contains:
- Visual comparison of feature distributions
- Accuracy metrics for each algorithm
- Confusion matrices and classification reports
- Discussion of which algorithm performed best
