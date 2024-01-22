# Predicting Car Prices in Australia with Random Forest Regression

**Overview:**
In this project, I aimed to develop a predictive model for estimating car prices in the Australian market. The prediction is based on key features such as brand, year, mileage, number of cylinders, and engine capacity. Leveraging the power of machine learning, I employed the Random Forest regression algorithm to create an accurate and reliable model.

**Dataset:**
The dataset used for this project was obtained from Kaggle, a popular platform for data science competitions and datasets. The dataset likely contained information on car listings in Australia, with key attributes including brand, manufacturing year, mileage, number of cylinders, and engine capacity.
Link for the dataset https://www.kaggle.com/datasets/nelgiriyewithana/australian-vehicle-prices

**Methodology:**

1. **Data Preprocessing:**

   - Conducted exploratory data analysis (EDA) to understand the distribution and relationships among the features.
   - Handled missing values and outliers to ensure the quality of the dataset.
   - Performed feature engineering to extract relevant information and enhance the predictive power of the model.

2. **Model Selection:**

   - Chose the Random Forest regression algorithm for its ability to handle complex relationships and provide robust predictions.
   - Split the dataset into training and testing sets to evaluate the model's performance.

3. **Model Training:**

   - Trained the Random Forest model on the training dataset, allowing it to learn patterns and correlations among the features.
   - Tuned hyperparameters to optimize the model's performance and prevent overfitting.

4. **Evaluation:**
   - Assessed the model's performance using metrics such as mean squared error, mean absolute error, and R-squared on the testing dataset.
   - Employed cross-validation techniques to ensure the generalizability of the model.

**Results:**
The developed Random Forest regression model demonstrated high accuracy and reliability in predicting car prices based on the selected features. It proved effective in capturing non-linear relationships and handling the complexities of the Australian car market.

**Conclusion:**
This project successfully addressed the challenge of predicting car prices in Australia, providing a valuable tool for both buyers and sellers in the automotive market. The Random Forest model showcased its strength in handling diverse features and delivering accurate predictions, contributing to informed decision-making in the car purchasing process.

**Model Deployment and Utilization:**
To bridge the gap between model development and practical use, the project was divided into two distinct Jupyter notebooks - "Model_Implementation" and "Model_Utilization."

1. Model Implementation:
   In the "Model_Implementation" notebook, the focus was on the development and training of the Random Forest Regression model. Key steps included data exploration, preprocessing, feature engineering, and the selection of the Random Forest algorithm for its suitability in predicting car prices. This notebook culminated in the exportation of the trained model, ready for deployment.

2. Model Utilization:
   The "Model_Utilization" notebook took on the responsibility of loading the pre-trained model and making it accessible for real-world predictions. Here, the exported model was loaded into the notebook, allowing for seamless integration into applications or services. Users can input relevant car features, such as brand, year, mileage, number of cylinders, and engine capacity, and receive predicted car prices. This section adds a practical dimension to the project, showcasing the model's usability beyond the development environment.
