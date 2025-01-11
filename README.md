# Price Prediction of Second-Hand Cars Using Deep Learning

This repository contains the code and data for predicting the price of second-hand cars using a deep learning model. The dataset used includes various features such as the car's on-road price (both old and current), years of usage, kilometers driven, ratings, condition, economy, top speed, horsepower, torque, and the current price.

## Model Architecture

The deep learning model is built using TensorFlow's Keras API. The model consists of a sequential architecture with the following layers:

- **Input Layer**: Accepts 8 input features.
- **Normalizer**: Normalizes the input data.
- **Hidden Layers**: Three dense layers with 128 neurons each and ReLU activation.
- **Output Layer**: A single neuron to predict the car's current price.


## Model Compilation

The model is compiled using the Adam optimizer with a learning rate of 0.1. The loss function used is `MeanAbsoluteError`, and the performance metric is `RootMeanSquaredError`.


## Training and Evaluation

The model is trained on the dataset and evaluated on validation and test sets. The results include the loss, error metrics, and price predictions for second-hand cars.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/price-prediction-second-hand-cars.git
   ```
2. Navigate to the project directory:
   ```bash
   cd price-prediction-second-hand-cars
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the training script:
   ```bash
   python train_model.py
   ```

## Results

The final validation and test loss, error metrics, and sample predictions are provided at the end of the training process.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions for improvement.


