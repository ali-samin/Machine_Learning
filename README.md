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


### Setup

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run data ingestion**:

    ```bash
    python src/data_ingestion.py
    ```

4. **Run data transformation**:

    ```bash
    python src/data_transformation.py
    ```

5. **Train the models**:

    ```bash
    python src/model_trainer.py
    ```

6. **Start the Flask application**:

    ```bash
    python src/app.py
    ```

7. **Access the web application** at `http://127.0.0.1:5000/`.

## Usage

1. Navigate to the web application URL.
2. Fill out the form with the student's details.
3. Click "Predict your Maths Score" to get the prediction.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make changes and commit them (`git commit -am 'Add new feature'`).
4. Push the branch (`git push origin feature/your-feature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The project utilizes machine learning models from Scikit-learn, XGBoost, and CatBoost.
- Thanks to the libraries and contributors that made this project possible.

```

Replace `https://github.com/your-username/your-repo.git` with the URL of your actual repository and adjust any details to fit your specific project needs.
