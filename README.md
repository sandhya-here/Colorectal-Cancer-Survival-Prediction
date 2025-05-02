🧬 Colorectal Cancer Survival Prediction

📌 Project Overview

This project aims to predict the survival status of colorectal cancer patients using a variety of demographic, clinical, and lifestyle factors. The model is trained using machine learning techniques (primarily logistic regression) on a structured dataset.

🗂️ Dataset Description

The dataset contains anonymized information of patients, including:

Demographic Details: Age, Gender, Race, Region, Urban/Rural

Clinical History: Family history, Previous cancer, Tumor aggressiveness, Stage at diagnosis

Lifestyle Factors: Diet type, BMI, Physical activity, Smoking & alcohol habits, Meat & fiber intake

Healthcare Access: Colonoscopy access, Insurance, Time to diagnosis, Treatment access

Treatment Records: Chemotherapy, Radiotherapy, Surgery, Follow-up adherence

Outcome Variables:

Survival_Status → Target (Binary)

Recurrence → Secondary optional target

Time_to_Recurrence → Useful for survival analysis

🧪 Objective
To build a classification model that predicts whether a patient is likely to survive colorectal cancer based on historical and lifestyle data.

🛠️ Tools & Libraries Used

Python

Pandas, NumPy – Data handling

Seaborn, Matplotlib – Data visualization

Scikit-learn – ML modeling, evaluation, and preprocessing

🔍 Project Steps

Data loading and inspection

Handling missing values and encoding categorical variables

Data scaling and splitting

Model training using Logistic Regression

Evaluation using  confusion matrix, and classification report

