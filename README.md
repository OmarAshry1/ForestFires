# Algerian Forest Fires Prediction 🌲🔥

## Overview

A machine learning project that predicts the Fire Weather Index (FWI) for Algerian forests using meteorological data. The model helps forest fire prevention by analyzing weather conditions and derived fire indices.

## Features

- **Input Parameters:**
  - Temperature (°C)
  - Relative Humidity (%)
  - Wind Speed (km/h)
  - Rainfall (mm)
  - FFMC (Fine Fuel Moisture Code)
  - DMC (Duff Moisture Code)
  - DC (Drought Code)
  - ISI (Initial Spread Index)
  - BUI (Buildup Index)

- **Output:**
  - FWI (Fire Weather Index)
  - Fire Risk Classification (Fire/No Fire)

## Project Structure

```
📦 Implementation
 ┣ 📂 models
 ┃ ┣ 📜 ridge.pkl
 ┃ ┗ 📜 scaler.pkl
 ┣ 📂 notebooks
 ┃ ┣ 📜 Cleaning and EDA.ipynb
 ┃ ┗ 📜 Model.ipynb
 ┣ 📂 templates
 ┃ ┣ 📜 home.html
 ┃ ┗ 📜 index.html
 ┣ 📜 application.py
 ┗ 📜 requirements.txt
```

## Model Performance

- **R-squared Score:** 0.96
- **Mean Absolute Error:** 0.86
- **Root Mean Square Error:** 1.12

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/algerian-forest-fires.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python application.py
```

4. Open your browser and navigate to `http://localhost:5000`

## Tech Stack

- Python 3.12
- scikit-learn
- pandas
- Flask
- HTML/CSS
- Jupyter Notebook

## Future Improvements

- [ ] Add more machine learning models
- [ ] Implement real-time weather data integration
- [ ] Add visualization dashboard
- [ ] Deploy to cloud platform

