# Anomaly Detection with Autoencoder

This project implements **Anomaly Detection** using different types of **Autoencoders**. The model is trained to learn normal patterns in data and identify anomalies based on reconstruction errors.

## Features
- Implements **Fully Connected Autoencoder (FCAE), Convolutional Autoencoder (CAE), and Overcomplete Autoencoder (OCAE)**.
- Learns to reconstruct normal data and detects anomalies with high reconstruction error.
- Used image augmentation techniques for training and testing purposes

## Types of Autoencoders Used
### **1. Fully Connected Autoencoder (FCAE)**
- Uses fully connected (dense) layers.
- Simple and effective for structured data.
- Encodes data into a compressed latent space.

### **2. Convolutional Autoencoder (CAE)**
- Uses convolutional layers to extract spatial features.
- Works well for image-based anomaly detection.
- Preserves local structures in data.

### **3. Overcomplete Autoencoder (OCAE)**
- Expands the input into a **higher-dimensional** latent space.
- Helps in learning **more expressive representations**.
- Improves anomaly detection by forcing the network to capture meaningful patterns.

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
Run the script using:
```bash
python autoencoder_anomaly_detection.py
```

## How It Works
1. The model is trained on **normal data**.
2. It learns to reconstruct normal patterns accurately.
3. Anomalies have **higher reconstruction errors**, making them detectable.
4. The **CAE** had the highest accuracy among the three.

## Author
D. Yokesh

## License
This project is open-source and available under the MIT License.

