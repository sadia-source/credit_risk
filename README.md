### Credit Risk Managment
This project aims to analyze and predict loan default risk using machine learning techniques. 
By leveraging key financial and personal attributes, we build predictive models to assist in credit decision-making.

### Here’s a short definition of each column:

person_age – Applicant's age.

person_income – Annual income of the applicant.

person_home_ownership – Type of home ownership (Rent, Own, Mortgage, Other).

person_emp_length – Years of employment.

loan_intent – Purpose of the loan (e.g., Personal, Medical, Education).

loan_grade – Loan risk grade (A–D, where A is the best).

loan_amnt – Loan amount requested.

loan_int_rate – Interest rate on the loan.

loan_status – Loan outcome (1 = Default, 0 = No Default).

loan_percent_income – Loan amount as a percentage of income.

cb_person_default_on_file – Whether the applicant has defaulted before (Y/N).

cb_person_cred_hist_length – Length of the applicant's credit history (in years



### Conclusion
This Loan Default Risk Checker allows for real-time predictions based on various loan applicant details, providing valuable insights into the likelihood of default. 
The script leverages a pre-trained machine learning model and user input to generate a simple "DEFAULT" or "NO DEFAULT" result. 
The accuracy of the Loan Default Risk Checker can be improved by incorporating additional features like credit scores, fine-tuning hyperparameters, and using advanced models such as XGBoost. Cross-validation can enhance generalization, while handling class imbalance with techniques like SMOTE or class weighting can improve prediction reliability.

