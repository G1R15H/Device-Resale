# Device-Resale
# Used Devices Selling Price Prediction and Recommendation System
Cloud based Second hand price prediction and Recommendation

This project aims to provide a data-driven solution for predicting the resale price of used devices in the second-hand market and offering recommendations to users based on a predefined benchmark. The system utilizes machine learning techniques, cloud deployment, and web development to achieve its goals.

## Usage
Ensure you have the required dependencies installed by running: pip install flask pandas scikit-learn
Run `flask_app.py` to start the Flask web application.
Access the application by visiting http://localhost:5000 in your web browser.(or the specific port number in your project)

## Data Preprocessing and Model Training
The Jupyter Notebook `Record.ipynb` and `usedmobile.ipynb` provides insights into the data preprocessing steps and the process of training the Multiple Linear Regression model. The notebook explains how the `used_device_data.csv` dataset is cleaned, features are selected, and the model is trained.

## Cloud Deployment
The application is designed to be deployed on cloud infrastructure. For deployment on AWS, follow these steps:

Set up an AWS EC2 instance.
Upload the necessary files to the instance.
Install required dependencies and libraries.
Run `flask_app.py` on the instance.

## Contributions
Contributions to this project are encouraged! Whether you're interested in enhancing the machine learning model, refining the user interface, or improving deployment, your contributions are valuable. To propose changes, submit a pull request.
