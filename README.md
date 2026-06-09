# Crop Recommendation System
## 💻 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
## Overview
The Crop Recommendation System is a Machine Learning-based web application that predicts the most suitable crop for cultivation based on soil and environmental conditions.

The system takes the following inputs:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Value
- Rainfall

Using these parameters, the trained machine learning model recommends the best crop to cultivate.

---

## Features

- Predicts suitable crops using machine learning.
- User-friendly web interface built with Flask.
- Fast and accurate recommendations.
- Supports multiple crop categories.


---

## Project Structure
Crop-Recommendation-System/
│
├── app.py                 # Flask application
├── model.pkl              # Trained ML model
├── requirements.txt       # Dependencies
├── Procfile               # Deployment configuration
│
├── templates/
│   └── index.html         # Frontend page
│
└── Crop_recommendation.ipynb  # Model training notebook


---

## Dataset Information

### Dataset Used
**Crop Recommendation Dataset** (`Crop_recommendation.csv`)

### Dataset Size
- Approximately **2,200 records (rows)**
- **8 columns**

### Features

| Feature | Description |
|----------|------------|
| N | Nitrogen content in soil |
| P | Phosphorus content in soil |
| K | Potassium content in soil |
| temperature | Temperature in °C |
| humidity | Relative humidity (%) |
| ph | Soil pH value |
| rainfall | Rainfall (mm) |
| label | Recommended crop |

### Number of Crop Classes
The dataset contains **22 crop categories**, including:

- Rice
- Maize
- Jute
- Cotton
- Coconut
- Papaya
- Orange
- Apple
- Muskmelon
- Watermelon
- Grapes
- Mango
- Banana
- Pomegranate
- Lentil
- Blackgram
- Mungbean
- Mothbeans
- Pigeonpeas
- Kidneybeans
- Chickpea
- Coffee

---

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/abdul-naveed-git/Crop-Recommendation-System
cd Crop-Recommendation-System
```
