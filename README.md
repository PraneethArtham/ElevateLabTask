# ElevateLabTask1

## 📌 What This Project Covers

This project walks through the following essential steps:

1. **Loading the dataset** – Getting the data into Python so we can work with it.
2. **Exploring the data** – Understanding what kind of values we have, and spotting missing or weird data.
3. **Fixing missing values** – Filling in blanks (like age or where someone boarded the ship) using smart guesses.
4. **Converting text to numbers** – Because machines don't understand "male" or "S", we turned these into numerical values.
5. **Scaling the numbers** – To help the machine treat all features equally, we scaled age and fare values.
6. **Removing outliers** – We spotted and removed extreme values that could mess up our predictions.
7. **Saving the cleaned data** – So we can use it for modeling later.

---

## 🛠️ Tools and Libraries Used

- **Pandas** – for handling the data
- **NumPy** – for numerical calculations
- **Seaborn & Matplotlib** – for data visualization
- **Scikit-learn** – for scaling and encoding


---

## What I Learned

- How to handle missing data using median and mode
- The difference between label encoding and one-hot encoding
- Why scaling data is necessary
- How to detect and remove outliers using IQR

---

## Common Interview Questions & My Answers

| **Q1:** What are types of missing data? 
        MCAR, MAR, MNAR 
| **Q2:** How do you handle categorical variables?  
        Label Encoding (for ordered), One-Hot Encoding (for unordered) 
| **Q3:** Normalization vs Standardization? 
        Normalization scales between 0 and 1; Standardization centers data around 0 
| **Q4:** How do you detect outliers? 
        Boxplots, IQR method 
| **Q5:** Why is preprocessing important?   
        It helps the model understand and learn better 
| **Q6:** One-hot vs label encoding? 
        One-hot = new columns for each category; Label = single column with numbers 
| **Q7:** How do you handle imbalanced data? 
      SMOTE, oversampling, undersampling |
| **Q8:** Can preprocessing affect accuracy? 
      Absolutely – clean data gives better predictions 


Thanks for checking this out 😊
