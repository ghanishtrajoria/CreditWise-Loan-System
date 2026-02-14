# CreditWise Loan System
## Project Description
This project focuses on automating the loan approval process using machine learning. It analyzes applicant details such as income, credit score, employment status, and other financial metrics to predict whether a loan application should be approved or rejected.
## Files in the Project
- **`Untitled.ipynb`**: A Jupyter Notebook containing the data analysis, data cleaning (handling missing values), exploratory data analysis (EDA), and machine learning model implementation.
- **`loan_approval_data.csv`**: The dataset used for training and testing the model. It contains information about applicants including their income, loan amount, credit score, and approval status.
## Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Seaborn & Matplotlib**: For data visualization.
- **Scikit-Learn**: For building and evaluating machine learning models.
## Dataset Features
The dataset includes the following columns:
- `Applicant_ID`: Unique identifier for the applicant.
- `Applicant_Income`: Income of the primary applicant.
- `Coapplicant_Income`: Income of the co-applicant.
- `Employment_Status`: Employment details (Productivity, Salaried, Self-Employed).
- `Age`: Age of the applicant.
- `Marital_Status`: Marital status.
- `Dependents`: Number of dependents.
- `Credit_Score`: Credit history score.
- `Existing_Loans`: Number of existing loans.
- `DTI_Ratio`: Debt-to-Income ratio.
- `Savings`: Total savings.
- `Collateral_Value`: Value of collateral provided.
- `Loan_Amount`: Amount of loan requested.
- `Loan_Term`: Duration of the loan.
- `Loan_Purpose`: Reason for the loan.
- `Property_Area`: Urban, Semiurban, or Rural.
- `Education_Level`: Education qualification (Graduate, Not Graduate).
- `Gender`: Gender of the applicant.
- `Employer_Category`: Category of employer.
- `Loan_Approved`: Target variable (Yes/No).
## How to Run
1. Ensure you have Python and Jupyter Notebook installed.
2. Install the required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
3. Open `Untitled.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells sequentially to see the analysis and model results.
## Author
Ghanisht Rajoria
