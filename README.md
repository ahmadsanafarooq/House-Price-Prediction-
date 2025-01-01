🚀 **Predicting House Prices Using Linear Regression!** 🏠📊  

I recently worked on an exciting project that leverages **Linear Regression** to predict house prices based on multiple features like location, condition, and garage availability. Here's a quick overview of what I did:  

---

### 🛠️ **Steps in the Project**:  
1️⃣ Loaded a real-world dataset on house prices and explored its features.  
2️⃣ Identified unique values in key columns such as `Location`, `Condition`, and `Garage`.  

3️⃣ Applied One-Hot Encodingto handle categorical features like `Location`, `Condition`, and `Garage` using `pd.get_dummies()`. This step ensured that the model understands the data without introducing bias.  

4️⃣ Built a clean dataset by merging dummy columns and dropping unnecessary columns to avoid multicollinearity.  

5️⃣ Developed a Linear Regression Model to predict the house price based on the following features:  
   - Area  
   - Bedrooms  
   - Bathrooms  
   - Floors  
   - Year Built  
   - Location and Condition (encoded features)  

6️⃣ Made predictions for different scenarios:  

Data preprocessing
-  is critical for building accurate models, especially when dealing with categorical data.  
- Using dummy variables helps eliminate redundancy and ensures the model interprets the data effectively.  
- Linear regression provides a solid foundation for understanding key factors influencing house prices.  

Download Dataset: https://www.kaggle.com/datasets/zafarali27/house-price-prediction-dataset].  
