# 🚀 Absenteeism Prediction at Work  

## 📋 Project Overview  
This project aims to predict employee absenteeism during work hours using machine learning techniques. The ability to foresee absenteeism allows organizations to make better-informed decisions, reorganize work processes, and maintain productivity.  

## ❓ Problem Statement  
Absenteeism, defined as "the absence from work during normal working hours resulting in temporary incapacity to execute regular work activity," is a common challenge for businesses. Understanding the patterns and factors that contribute to absenteeism can improve decision-making and resource allocation, thereby reducing the negative impact on productivity.  

### 🎯 Business Objective  
The objective is to determine whether an employee, based on specific characteristics (e.g., distance from the workplace, education level, family structure), is likely to be absent and for how many hours.  

## 📊 Dataset  
The dataset used in this project is derived from an existing study on absenteeism prediction. This is a **secondary dataset**, meaning it was collected and prepared by a third party.  

## 📑 Dataset Description

This dataset contains various details about employee absenteeism. Below is a description of each attribute included in the dataset:

1. **ID** 📛  
   - Individual identification for each entry.

2. **Reason for Absence** 🏥  
   - The reasons for absence are categorized as follows:
     - **1**: Certain infectious and parasitic diseases
     - **2**: Neoplasms
     - **3**: Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism
     - **4**: Endocrine, nutritional and metabolic diseases
     - **5**: Mental and behavioural disorders
     - **6**: Diseases of the nervous system
     - **7**: Diseases of the eye and adnexa
     - **8**: Diseases of the ear and mastoid process
     - **9**: Diseases of the circulatory system
     - **10**: Diseases of the respiratory system
     - **11**: Diseases of the digestive system
     - **12**: Diseases of the skin and subcutaneous tissue
     - **13**: Diseases of the musculoskeletal system and connective tissue
     - **14**: Diseases of the genitourinary system
     - **15**: Pregnancy, childbirth, and the puerperium
     - **16**: Certain conditions originating in the perinatal period
     - **17**: Congenital malformations, deformations, and chromosomal abnormalities
     - **18**: Symptoms, signs, and abnormal clinical and laboratory findings, not elsewhere classified
     - **19**: Injury, poisoning, and certain other consequences of external causes
     - **20**: External causes of morbidity and mortality
     - **21**: Factors influencing health status and contact with health services
     - **22**: Patient follow-up
     - **23**: Medical consultation
     - **24**: Blood donation
     - **25**: Laboratory examination
     - **26**: Unjustified absence
     - **27**: Physiotherapy
     - **28**: Dental consultation

3. **Date** 📅  
   - The date of absence.

4. **Transportation Expense** 💸  
   - Costs related to business travel, including fuel, parking, and meals.

5. **Distance to Work** 🚗  
   - The distance from home to work, measured in kilometers.

6. **Age** 🎂  
   - The age of the individual, in years.

7. **Daily Work Load Average** 🕒  
   - The average daily workload, measured in minutes.

8. **Body Mass Index (BMI)** ⚖️  
   - The body mass index of the individual.

9. **Education** 🎓  
   - A categorical variable representing different levels of education.

10. **Children** 👶  
    - The number of children in the family.

11. **Pets** 🐾  
    - The number of pets in the family.

12. **Absenteeism Time in Hours** ⏱️  
    - The total time of absence, measured in hours.


### 🔧 Data Preprocessing  
The raw dataset underwent preprocessing to address common data issues, such as:  
- ⚠️ Handling missing or inconsistent values.  
- 🛠 Standardizing data formats.  
- 🧹 Preparing the data for statistical analysis and machine learning.  

## 🧠 Methodology  
1. **🔍 Exploratory Data Analysis (EDA):** Understand the data structure and identify key patterns.  
2. **🛠 Feature Engineering:** Select and transform relevant features to improve model performance.  
3. **🤖 Model Building:** Develop and train a predictive model using **logistic regression** from **scikit-learn**.  
4. **📏 Evaluation:** Validate the model using appropriate metrics to ensure accuracy and reliability.  
5. **📈 Data Visualization:** Present results and insights using **Tableau** for clarity and business impact.  

## 🛠 Key Features and Tools  
- 🐍 **Python** for data analysis and machine learning.  
- ⚙️ **scikit-learn** for logistic regression and predictive modeling.  
- 📊 **NumPy** and **pandas** for data manipulation and analysis.  
- 🌐 **Tableau** for interactive data visualization.  

## 🔗 Tableau Visualization  
Explore the interactive visualizations that showcase key findings from this project:  
- [🌐 Link to Tableau Dashboard](https://dub01.online.tableau.com/#/site/belhamiciabderrahmane-6fa2ab3471/workbooks/2188768?:origin=card_share_link)
- [📊 Detailed Visualization Analysis](./visualization.md) *(Comprehensive analysis of model predictions and insights)*

## 🏆 Results  
The project demonstrates a practical approach to predicting absenteeism and provides actionable insights for business decision-making.  

## ✅ Conclusion  
By leveraging machine learning and predictive modeling, this project offers a robust solution to understanding and managing absenteeism in the workplace, ensuring smoother operations and increased productivity.  
