# Innovative Framework for Cattle Breed Differentiation

This project is a Machine Learning based web application that identifies and differentiates Indian cattle breeds from images.

The system uses a trained deep learning model to analyze cattle images and predict the breed with high accuracy. The web interface allows users to upload an image and instantly receive the predicted breed.

## Features

* Detects Indian cattle breeds using deep learning
* Simple web interface for image upload
* Fast prediction using trained ML model
* Docker support for easy deployment

## Project Structure

```
app/               # Application logic
templates/         # HTML templates
static/            # CSS, JS and assets
main.py            # Main application file
requirements.txt   # Python dependencies
version4.pt        # Trained ML model
Dockerfile         # Container setup
```

## Installation

Clone the repository:

```
git clone https://github.com/aayush4374/innovative_framework_for_cattle_breed_differentiation.git
```

Go into the project directory:

```
cd innovative_framework_for_cattle_breed_differentiation
```

Create a virtual environment:

```
python -m venv venv
```

Activate the environment (Windows):

```
venv\Scripts\activate
```

Install dependencies:

```
pip install -r requirements.txt
```

## Run the Application

```
python main.py
```

Then open your browser and go to:

```
http://localhost:8000
```

Upload a cattle image and the system will predict the breed.

## Technologies Used

* Python
* PyTorch
* Computer Vision
* Machine Learning
* Web Framework
* Docker

## Author
Aayush Singhal <br>
Ayush Gupta <br>
Anoop Prakash Yadav <br>
Ankit Kumar <br>

