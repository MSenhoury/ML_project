---

# 💼 Employee Salary Prediction

## DescriptionThis project involves developing a machine learning model to predict employee salaries based on their experience, test scores, and interview scoresThe model is trained using **linear regression** and is deployed via a **Flask** web application, allowing users to input employee data and receive salary predictions

## Features
-Predicts salary based on
  -Years of experienc
  -Test scor
  -Interview scor
-Interactive web interface for user input and salary predictio

## Prerequisites
Ensure you have the following Python packages installed:
```bashpip install numpy pandas scikit-learn flas
```


## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/MSenhoury/ML_project.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd ML_project
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```


## Usage
1. **Train the model:**
   -Run `model.py` to train the linear regression model using the provided dataset (`hiring.csv`). The trained model is saved as `model.pkl`
2. **Start the Flask application:**
   ```bash
   python app.py
   ```

3. **Access the web application:**
   -Open your web browser and navigate to `http://localhost:5000`
   -Input the employee's experience, test score, and interview score to receive a salary prediction

## Project Structure
- `app.py`:Contains the Flask web application code
- `model.py`:Trains the linear regression model and saves it using the `pickle` library
- `hiring.csv`:Dataset containing employee experience, test scores, interview scores, and corresponding salaries
- `model.pkl`:Serialized linear regression model
- `templates/`:Directory containing HTML templates for the Flask application
- `requirements.txt`:Lists the Python packages required to run the project
- `Procfile`:Specifies the commands that are executed by the app on startup (used for deployment)
- `request.py`:Contains code to send requests to the Flask application (optional)

## Technologies Used
- **Programming Languages:**Pytho
- **Libraries:**NumPy, Pandas, Scikit-learn, Flas
- **Web Framework:**Flas
- **Deployment:**Render (as indicated by the Procfile

## Author
- **Mohamed Senhoury**

## LicenseThis project is licensed under the MIT License

---
