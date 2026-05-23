# Loan-Approval-Classification-Model
A machine learning model using classification to determine loan approval eligibility using Random Forest classification.
---

# How to Run

1. **Install required tools:**
   pip install pandas scikit-learn kaggle

2. **Set up Kaggle:** If you are using Google Colab, add your Kaggle API key to the Secrets menu and name it KAGGLE_KEY.

3. **Run the code:**
   Execute your script. It will automatically download the data and run everything.


# What the Code Does

- **Step 1: Downloads the Data:** Automatically fetches the loan dataset directly from Kaggle and extracts it.
- **Step 2: Cleans the Data:** Fills in any blank cells automatically (using the median for numbers and the word "Unknown" for text) and converts text descriptions into numbers.
- **Step 3: Initial Training:** Splits the data into an 80% training set and a 20% testing set to calculate a baseline accuracy score.
* **Step 4: Finds the Best Settings:** Uses Grid Search to automatically test different settings to find the most accurate model.
* **Step 5: Predicts a New Applicant:** Takes applicant profile and outputs whether their loan is approved or denied, along with the exact probability percentage.
