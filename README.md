X Education Lead Scoring Model
Overview
X Education, an online education provider for industry professionals, faces a challenge where only about 30% of its daily generated leads convert into paying customers. Leads are generated through website visits—via organic searches, digital marketing channels, or referrals—and are further qualified when visitors submit their contact details. To improve conversion rates, this project develops a logistic regression model that assigns a lead score (ranging from 0 to 100) to each prospect. A higher score indicates a "hot lead" with a greater likelihood of conversion, enabling the sales team to prioritize their outreach effectively.

Repository Structure
Lead Score Case Study Pradeep_Shivam_LeadScore_CaseStudy.ipynb
Jupyter Notebook containing the complete data analysis, model development, and evaluation process.

Assignment Subjective Questions.pdf
Document with detailed answers to the project’s subjective questions.

Lead Score Case Study.pdf
Final presentation summarizing insights, recommendations, and findings.

Leads.csv
Dataset used for the analysis.

Leads Data Dictionary.xlsx
Data dictionary describing each feature in the dataset.

Summary.pdf
Comprehensive summary of the methodology and key steps undertaken in the analysis.

Methodology
Data Acquisition and Preprocessing

Imported the dataset Leads.csv.
Performed data cleaning to handle missing values, inconsistent entries, and outliers.
Exploratory Data Analysis (EDA)

Conducted an in-depth analysis to understand feature distributions, relationships, and potential predictors.
Feature Engineering

Created dummy variables for categorical features and normalized key attributes to enhance model performance.
Model Development

Split the data into training and test sets.
Developed a logistic regression model to estimate the probability of lead conversion.
Model Evaluation

Assessed model performance using ROC curves, recall-accuracy-specificity metrics, and other relevant evaluation criteria.
Tuned model parameters to achieve optimal predictive accuracy.
Lead Scoring

Generated a lead score between 0 and 100 based on the logistic regression output.
Higher scores indicate a higher likelihood of conversion, enabling targeted engagement by the sales team.
Flexibility and Future Enhancements
The model is designed with scalability in mind. Its modular structure allows for:

Easy updates to the preprocessing and feature engineering pipelines.
Adjustments in response to new business requirements.
Integration of additional predictive features as more data becomes available.
Conclusion
This project demonstrates how logistic regression can be effectively applied to score leads, enabling X Education to prioritize high-potential prospects and ultimately improve conversion rates. The detailed analysis and flexible design of the model ensure that it can adapt to future business needs, making it a valuable tool for strategic decision-making.
