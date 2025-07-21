# SIMPLE-RNN-IMDB

A simple project demonstrating sentiment analysis on the IMDB movie reviews dataset using a Recurrent Neural Network (RNN) in Keras.

## Features

- Loads and preprocesses the IMDB dataset
- Builds and trains a simple RNN model for binary sentiment classification
- Saves and loads trained model weights (`simple_rnn_imdb.h5`)
- Includes example Jupyter notebooks for training and prediction

## Project Structure

- `main.py` - Main script for training and evaluating the RNN model
- `simple_rnn_imdb.h5` - Saved Keras model weights
- `simplernn.ipynb` - Jupyter notebook for model training and exploration
- `embedding.ipynb` - Jupyter notebook for embedding visualization or analysis
- `prediction.ipynb` - Jupyter notebook for making predictions with the trained model
- `requirements.txt` - Python dependencies

## Getting Started

1. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

2. **Train the model:**
   ```sh
   python main.py
   ```

3. **Run the notebooks:**
   Open `simplernn.ipynb` or `prediction.ipynb` in Jupyter Notebook or JupyterLab.

## Requirements

- Python 3.7+
- TensorFlow / Keras
- NumPy

See `requirements.txt` for details.

## License
Apache-2.0 license

See
