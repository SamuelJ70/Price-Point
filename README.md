# Price-Point

This application allows a user to provide a set of specifications he/shedesires in a mobile phone , based on the provided specification the application gives an estimated price. This functionality is acheived using amachine learning model which was trained using a dataset which was created from publicly available data obtained from various sources in the internet.

In the process of developing this application , the full spectrum of tasks such as Data collection , Data preprocessing , Feature engineering , Model Selection , Model evaluation and Model finetuning involved in the creation of a predictive model have been covered.


Multiple models have been created using different algorithms ( Random forest regressor , Feed Forward Neural Network ). The user can choose which model he wishes the application to utilize and also compare the results obtained from each of them. 

Finally , The application has been deployed using Flask to a convinient interface for users to access. Also as part of the deployed application is an additional dashboard component which provides various insights about the collected dataset using appropriate graphical components. Users can explore and investigate to get a better understanding. 

## Prerequisites

- Python 3.10 or higher 
- pip (Python package installer)

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/SamuelJ70/Price-Point.git
   cd Price-Point 



2. Create and activate a Python virtual environment:
   python3 -m venv venv
   ```bash 
   source venv/bin/activate  # On Windows, use venv\Scripts\activate

3. Install required libraries using requirements.txt:
   ```bash 
   pip install -r requirements.txt 

4. Run the Flask application:
   ```bash 
   flask run

5. Access the application  at :
   ```bash 
   'http://localhost:5000'.
