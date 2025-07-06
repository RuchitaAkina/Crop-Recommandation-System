**Crop Recommendation System**

A machine learning-based web application that recommends the most suitable crop to cultivate based on soil and environmental parameters.  
It uses a trained classification model along with MinMax scaling to predict optimal crops for better yield.

**Features**

- Predicts the best crop based on input features
- Built using Python, Flask, and Machine Learning
- User-friendly web interface with HTML templates
- Uses `MinMaxScaler` and a trained `.pkl` model

**Project Structure**

templates/

-[HTML files]
-app1.py # Flask web app
-crop.ipynb # Model training and evaluation notebook
-minmaxscaler.pkl # Scaler used during training
-model.pkl # Trained ML model

**Technologies Used**

- Python
- Flask
- scikit-learn
- pandas
- NumPy
- HTML (for web UI)

**Input Features**

-The model uses the following parameters for prediction:
-N (Nitrogen content in soil)
-P (Phosphorus content)
-K (Potassium content)
-Temperature
-Humidity
-pH
-Rainfall
