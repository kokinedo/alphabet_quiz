# Alphabet Quiz App

The Alphabet Quiz App is a web application that helps users practice and enhance their recognition of handwritten alphabets. The app uses a Convolutional Neural Network (CNN) model to identify the alphabets drawn by the user. The application is built using Flask and TensorFlow/Keras.

# Demo:
![](https://github.com/kokinedo/alphabet_quiz/blob/main/demo/demo.gif)

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Future Plans](#future-plans)
5. [License](#license)

## Features

- Users can practice recognition of handwritten alphabets
- Users can contribute to the dataset by providing more handwritten samples
- The application uses a Convolutional Neural Network (CNN) to recognize the alphabets

## Installation

1. Clone the repository:

`git clone https://github.com/kokinedo/alphabet-quiz.git`


2. Install the required packages:

`pip install -r requirements.txt`


3. Run the application:

`python app.py`


## Usage

1. Access the application on your browser at `http://localhost:5000`.
2. Choose "Practice" to start practicing alphabet recognition or "Add Data" to contribute to the dataset.
3. In "Practice" mode, draw the alphabet shown and submit it. The app will tell you if your attempt is correct or not.
4. In "Add Data" mode, draw the alphabet shown and submit it. The app will store your drawing as part of the training dataset.

## Future Plans

- Deploy the application on a web server to make it accessible to a wider audience. This can be achieved by using platforms like Heroku, AWS, or Google Cloud Platform.
- Implement user authentication and a leaderboard system to make the application more interactive and competitive.
- Continuously train and improve the CNN model with new data and better architectures.

