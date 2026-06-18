House Price Prediction using Multiple Linear Regression (NumPy)

A machine learning project that predicts house prices using Multiple Linear Regression implemented from scratch with NumPy.

This project demonstrates the complete workflow of a regression problem, including:

Data loading and preprocessing
Building the design matrix manually
Calculating model parameters using the Normal Equation
Making predictions on custom user input
Evaluating model performance using the R² score
Comparing training and testing performance using a train-test split
📌 Project Overview

The objective of this project is to estimate the price of a house based on various features such as:

Square footage
Number of bedrooms
Number of bathrooms
Year built
Lot size
Garage size
Neighborhood quality

Instead of using pre-built regression models from machine learning libraries, the model parameters are computed manually using linear algebra concepts.

This project helped strengthen understanding of:

Multiple Linear Regression
Design Matrix
Matrix Multiplication
Normal Equation
Moore-Penrose Pseudoinverse
Model Evaluation using R² Score
🛠️ Technologies Used
Python 3
NumPy
Pandas
Scikit-learn
📂 Dataset Features
Feature	Description
Square_Footage	Total area of the house in square feet
Num_Bedrooms	Number of bedrooms
Num_Bathrooms	Number of bathrooms
Year_Built	Construction year
Lot_Size	Land area in acres
Garage_Size	Number of garage spaces
Neighbourhood_Quality	Neighborhood rating (0–10)
House_Price	Target variable

📁 Project Structure
house-price-prediction/
│
├── house_price_regression_dataset.csv
├── house_price_prediction.py
├── README.md
└── requirements.txt

Through this project, I gained hands-on experience with:

Matrix operations using NumPy
Building a regression model without high-level libraries
Understanding the importance of the intercept term
Model validation using train-test splitting
Interactive prediction systems

🔮 Future Improvements
Feature scaling and normalization
Outlier detection and handling
Cross-validation
Gradient Descent implementation
Regularization techniques (Ridge and Lasso Regression)
Data visualization using Matplotlib
Web deployment using Flask or Streamlit
🤝 Contributing

Contributions, suggestions, and feedback are welcome.

Feel free to fork the repository, create a new branch, and submit a pull request.

👨‍💻 Author:
Adithya,
B.Tech Computer Science and Engineering student with interests in:
Machine Learning


If you found this project useful, consider giving it a ⭐ on GitHub.
