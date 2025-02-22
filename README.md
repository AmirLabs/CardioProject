# Cardiovascular Disease Prediction

## Overview
A deep learning model using TensorFlow to predict cardiovascular disease based on patient health data.

## Features
- Deep Neural Network with multiple layers.
- Data normalization with MinMaxScaler.
- Categorical crossentropy loss & Adam optimizer.

## Requirements
Install dependencies:
```bash
pip install numpy pandas tensorflow scikit-learn
```

## How to Run
1. Clone the repo & navigate to the directory:
   ```bash
   git clone https://github.com/your-username/cardio-prediction.git
   cd cardio-prediction
   ```
2. Place `cardio_train1.csv` in the project folder.
3. Run the script:
   ```bash
   python train.py
   ```

## Model
- **Input**: 11 features  
- **Hidden Layers**: 3 layers (ReLU activation)  
- **Output**: 2 neurons (softmax activation)  
- **Training**: 10 epochs, batch size 100  

## License
MIT License.
