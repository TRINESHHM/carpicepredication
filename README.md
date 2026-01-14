🚗 Car Price Prediction Web Application

A professional Machine Learning–based web application that predicts the price of used cars using historical data and user inputs. The system is built with Python, Flask, and Linear Regression, providing an easy-to-use interface for real-time predictions.

--------------------------------------------------

Project Description

Estimating the correct price of a used car is often challenging due to multiple influencing factors. This project addresses that problem by using a Machine Learning model trained on real-world car data to predict prices accurately.

The application allows users to enter car details and instantly receive a predicted market price.

--------------------------------------------------

Machine Learning Approach

Algorithm: Linear Regression  
Dataset: Quikr Used Car Dataset  
Data Processing: Cleaning, feature selection, and transformation  
Model Storage: Serialized using Pickle (.pkl file)

--------------------------------------------------

Technologies & Tools

Programming Language: Python  
Web Framework: Flask  
Libraries: Pandas, NumPy, Scikit-learn  
Frontend: HTML, CSS  
Development Tool: Jupyter Notebook  

--------------------------------------------------

Project Structure

carpicepredication/

static/                     - Static files (CSS, images)  
templates/                  - HTML templates  

application.py              - Flask application entry point  
LinearRegressionModel.pkl   - Trained ML model  
Cleaned_Car_data.csv        - Preprocessed dataset  
quikr_car.csv               - Raw dataset  
Quikr Analysis.ipynb        - Data analysis and training notebook  
Procfile                    - Deployment configuration  
requirements.txt            - Project dependencies  
demo.png                    - Application UI screenshot  
predict.png                 - Prediction output screenshot  
README.md                   - Project documentation  

--------------------------------------------------

Installation & Execution

Step 1: Clone the Repository
git clone https://github.com/TRINESHHM/carpicepredication.git
cd carpicepredication

Step 2: Install Required Dependencies
pip install -r requirements.txt

Step 3: Run the Application
python application.py

Step 4: Access the Web App
Open browser and go to:
http://127.0.0.1:5000/

--------------------------------------------------

Key Features

- Real-time car price prediction  
- Clean and user-friendly web interface  
- Machine Learning–powered backend  
- Easy to extend with advanced models  
- Ready for cloud deployment  

--------------------------------------------------

Future Enhancements

- Integrate advanced ML algorithms (Random Forest, XGBoost)  
- Improve UI/UX design  
- Deploy on cloud platforms like Render or AWS  
- Add more input parameters for higher accuracy  

--------------------------------------------------

Author

Name: Trinesh H M  

LinkedIn:
https://in.linkedin.com/in/trinesh-hm-016512371  

GitHub:
https://github.com/TRINESHHM  

--------------------------------------------------

Project Repository

https://github.com/TRINESHHM/carpicepredication

--------------------------------------------------

If you find this project useful, please consider giving it a star ⭐
