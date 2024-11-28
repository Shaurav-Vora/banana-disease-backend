# Banana Disease Prediction API

This project provides a RESTful API for predicting banana leaf diseases using a deep learning model. Users can upload an image of a banana leaf, and the API will return a prediction indicating whether the leaf is healthy or affected by diseases such as Black Sigatoka or Fusarium wilt.

`**However, note that this is the backend API only. For frontend UI, visit [here](https://github.com/Shaurav-Vora/banana-disease-frontend)**`

---

## Features
- **Disease Detection**: Identifies banana leaf conditions (e.g., Black Sigatoka, Fusarium wilt, Healthy).
- **REST API**: Simple interface to upload an image and receive a prediction.
- **Preprocessing**: Handles image resizing and normalization automatically.

---

## Requirements
- Python 3.7 or higher
- Required Python packages:
  - Flask
  - Flask-CORS
  - TensorFlow
  - NumPy

You can install the dependencies using:
```bash
pip install -r requirements.txt
```
# Clone the repository
git clone <repository-url>
cd <repository-folder>
