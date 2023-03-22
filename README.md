![download (2)](https://user-images.githubusercontent.com/57935250/226848239-e7d04ccf-8dc3-46ac-b4a8-a8f32e08c377.jpeg)
# Flight Price Prediction Machine Learning Application
This is a machine learning application that uses historical flight data to predict the price of future flights. The application is built using Python and scikit-learn, and it includes a web interface where users can enter flight details and get a predicted price for their desired flight.

## Installation
To install and run this application, follow these steps:

1. Clone this repository to your local machine.
2. Create a new virtual environment using virtualenv or conda.
3. Activate the virtual environment.
4. Install the dependencies using pip install -r requirements.txt.
5. Run the app.py file to start the application.
 
## Usage
To use the application, open your web browser and go to http://localhost:5000. You will see a simple form where you can enter the following information:

1. Departure city
2. Destination city
3. Departure date
4. Number of passengers
Once you have entered this information, click on the "Predict Price" button to get a predicted price for your desired flight. The application uses a machine learning model that has been trained on historical flight data to make this prediction.

## Training the Model
If you want to train the machine learning model yourself, you can use the train.py file. This file contains the code to preprocess the historical flight data, train a machine learning model using scikit-learn, and save the trained model to a file. You can modify this code to use your own data and machine learning algorithm if you wish.

## Acknowledgements
This project was inspired by the work of many researchers and developers in the field of machine learning and data science. We would like to acknowledge their contributions and thank them for their work.
