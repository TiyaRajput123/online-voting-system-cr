# Online Voting System for CR of a Class
This project presents a machine learning-based solution to predict the **most suitable Class Representative (CR)** using student feedback and voting patterns. Multiple classification algorithms are trained and evaluated on real student data to determine the most accurate predictor.

##  Project Highlights

-  **Objective**: Predict the best CR candidate using student feedback
-  **Tech Stack**: Python, Jupyter Notebook, pandas, scikit-learn
-  **Dataset**: Contains over 560+ records of student opinions and preferences

##  Machine Learning Models Used

-  Support Vector Machine (SVM)
-  Logistic Regression
-  Naive Bayes
-  Random Forest Classifier


##  Evaluation Metrics

-  Accuracy Score
-  Confusion Matrix
-  Classification Report


##  Folder Structure

Online-Voting-System-CR/
│
├── Online_Voting_System_For_CR.ipynb # Jupyter Notebook with full code and outputs
├── DataSet1_final.csv # Cleaned and labeled student feedback dataset
├── README.md # This file


##  How to Run

1. Clone the repository or download the ZIP
2. Open ` Online_Voting_System_For_CR.ipynb` in **Jupyter Notebook**
3. Ensure `DataSet1_final.csv` is in the same directory
4. Run all cells to preprocess data, train models, and evaluate performance

---

## 📈 Results

Out of all the models tested, **Naive Bayes** achieved the highest accuracy of **99%**, validated using confusion matrix and classification report.
