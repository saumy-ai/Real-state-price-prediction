# Real Estate Data Science Application

## Project Overview
This project is a **Real Estate Data Science Application** that provides insights, recommendations, and predictions for house and flat prices. It leverages machine learning techniques to analyze data extracted from **99acres.com**, offering users an intelligent tool for property price estimation.

## Features
- **Web Scraping**: Data extraction from **99acres.com** for real estate analysis.
- **Data Preprocessing**: Cleaning, handling missing values, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Visualizing trends and relationships in the real estate market.
- **Dimensionality Reduction**: Using **PCA** and feature selection techniques for better model performance.
- **Machine Learning Models**:
  - **XGBoost**
  - **Gradient Boosting**
  - **Support Vector Machine (SVM)**
  - **Random Forest** (Best Model with **91% R² score**)
- **Feature Importance Analysis**: Identifying key attributes affecting real estate pricing.
- **User-Friendly Prediction System**: Predict house prices based on user-input features.

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Processing)
- **Scikit-Learn, XGBoost, LightGBM** (Machine Learning)
- **BeautifulSoup, Scrapy** (Web Scraping)
- **Matplotlib, Seaborn** (Data Visualization)
- **Flask/Django** (For Web Interface, if applicable)

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/real-estate-data-science.git
   cd real-estate-data-science
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application (if applicable):
   ```sh
   python app.py
   ```

## Dataset
The dataset is sourced via web scraping from **99acres.com**. It includes features such as:
- **Location**
- **Property Type**
- **Area (sq. ft.)**
- **Price**
- **Number of Bedrooms, Bathrooms, and Balconies**
- **Nearby Amenities**

## Model Performance
The **Random Forest** model achieved the best performance with an **R² score of 91%**, making it the most reliable choice for price prediction.

## Future Enhancements
- Integration of **deep learning models** for price prediction.
- Deployment as a **web-based application**.
- Expansion to include **rental price prediction**.
- Addition of **geo-spatial analysis** for location-based recommendations.

## Contribution
Feel free to contribute by submitting pull requests. For major changes, open an issue to discuss proposed modifications.

## License
This project is licensed under the **MIT License**.

---
**Author:** [SAUMYA]  
**GitHub:** [https://github.com/saumy-ai]  
**Email:** [saumyav395@gmail.com]
