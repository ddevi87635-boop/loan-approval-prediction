PROBLEM STATEMENT: Loan Approval Prediction Tool Category

 Software Theme: Financial Technology Description: Small lenders and cooperative institutions manually assess routine loan applications using fixed rules of                       thumb, which is slow for simple cases and can lead to inconsistent decisions between different applicants with similar profiles.
Expected Solution: ● A software solution that predicts whether a loan application is likely to be approved or rejected, based on applicant details such as income, existing credit                             history,and requested loan amount.
                         ● Should be trained on a defined dataset and clearly report how it arrived at its prediction (key contributing factors). 
                         ● Should present the outcome along with a confidence level, not just a plain approve/reject label.
                         ● Should make clear that the tool is a decision-support aid and not a final lending decision.  
                         
PROPOSAL SOLUTION:
           Collect applicant and loan details.
           Process the data using Python.
           Predict approval using Machine Learning.
           Store details in MySQL.
           Display Approved/Rejected result through the web app.
           
ARCHITECTURE:
User
  ↓
HTML + CSS + JavaScript
  ↓
Flask REST API
  ↓
Pandas + NumPy
  ↓
Machine Learning Model
(Scikit-learn)
  ↓
Prediction
  ↓
SQLite / MySQL
  ↓
Result displayed to User


STACK USED:
           Frontend: HTML + CSS + JavaScript
           Backend: Python + Flask
           ML: Scikit-learn + Pandas + NumPy
           Database: SQLite
           Model: Random Forest
           IDE: VS Code
           
Team members:
           K.DURGA DEVI
           J.GOKULAPRIYA
           S.DHARANEESAWARAN
