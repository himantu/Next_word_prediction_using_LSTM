# Next Word Prediction using LSTM

## Overview

This project is a **Next Word Prediction Web Application** built using an **LSTM (Long Short-Term Memory) neural network**.
The model predicts the **most probable next word** based on a given input sentence.

The application uses **Streamlit** to provide a simple and interactive user interface.

---

## Features

* LSTM-based deep learning model
* Predicts the next word from a given sentence
* Simple Streamlit web interface
* Easy deployment using Git and cloud platforms

---

## Tech Stack

* Python
* TensorFlow / Keras
* Streamlit
* NumPy
* Git & GitHub

---

## Project Structure

```
next-word-prediction
│
├── app.py
├── lstm_model.h5
├── tokenizer.pkl
├── max_len.pkl
├── requirements.txt
├── runtime.txt
├── README.md
└── .streamlit
      └── config.toml
```

---

## Clone the Repository

```
git clone https://github.com/yourusername/next-word-prediction.git
cd next-word-prediction
```

---

## Install Dependencies

```
pip install -r requirements.txt
```

---

## Run the Application

```
streamlit run app.py
```

After running the command, open the browser and go to:

```
http://localhost:8501
```

---

## Deployment

To deploy the application:

1. Push the project to GitHub.
2. Connect the repository to your cloud platform.
3. Set the build command:

```
pip install -r requirements.txt
```

4. Set the start command:

```
streamlit run app.py --server.port 10000 --server.address 0.0.0.0
```

The platform will automatically build and deploy the application.

---

## Example

Input:

```
Machine learning is
```

Predicted Output:

```
fun
```

---

## Author

Himantu 
