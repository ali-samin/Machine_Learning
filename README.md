# Student Performance Prediction

## Overview

This project aims to predict student performance based on various input features such as gender, race/ethnicity, parental education level, lunch type, test preparation course, and scores in reading and writing. The solution utilizes machine learning models to provide predictions for student math scores.

## Project Structure

- **`data_ingestion.py`**: Handles data ingestion by reading and splitting the dataset into training and test sets.
- **`data_transformation.py`**: Preprocesses data, including handling missing values, encoding categorical variables, and scaling numerical features. Saves the preprocessing object.
- **`model_trainer.py`**: Trains and evaluates multiple regression models, selecting the best-performing model.
- **`predict_pipeline.py`**: Utilizes the trained model and preprocessing object to make predictions on new data.
- **`app.py`**: A Flask web application that accepts user input and displays predictions.
- **`home.html`**: HTML form for user input.
- **`requirements.txt`**: List of Python package dependencies.
- **`setup.py`**: Script for setting up the project environment.
data_ingestion.py: Data ingestion script for reading and splitting data.
data_transformation.py: Data transformation script for preprocessing data.
model_trainer.py: Model training script for training and evaluating models.
## Getting Started

### Prerequisites

Ensure Python 3.7 or higher is installed. Install the required packages by running:

```bash
pip install -r requirements.txt
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repo.git
cd your-repo
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Run the data ingestion script to prepare the data:

bash
Copy code
python src/data_ingestion.py
Run the data transformation script to preprocess the data:

bash
Copy code
python src/data_transformation.py
Train the models:

bash
Copy code
python src/model_trainer.py
Start the Flask web application:

bash
Copy code
python src/app.py
Open a web browser and go to http://127.0.0.1:5000/ to access the web application.

Usage
On the home page, fill out the form with the student's details, including gender, race/ethnicity, parental education level, lunch type, test preparation course, and scores in reading and writing.
Click the "Predict your Maths Score" button to get a prediction of the student's performance.
Contributing
If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The project uses various machine learning models including RandomForestRegressor, XGBRegressor, and CatBoostRegressor.
Special thanks to the contributors and libraries used in this project, including Scikit-learn, XGBoost, CatBoost, and Flask.
