# Training a Neural Network

This repository focuses on **training and evaluating a neural network**
using **supervised learning**. It explores model architecture, training behavior,
and performance evaluation on a structured dataset.

## Goals
1. **Prepare data** for neural network training (preprocessing and splitting).
2. **Train a feedforward neural network** using supervised learning.
3. **Evaluate model performance** using appropriate metrics.
4. **Analyze training behavior**, including loss and/or accuracy curves.

## Data
- **Source:** Coursework dataset
- **Unit of analysis:** Individual observations
- **Target variable:** Supervised learning outcome (classification or regression)
- **Features:** Input variables used for training the neural network

If the dataset is not included, see `data/README.md` for instructions.

## Methods
- **Model:** Feedforward neural network
- **Framework:** Neural network implementation as shown in the notebook
- **Training:**  
  - Train/validation split  
  - Optimization via gradient descent  
- **Evaluation:**  
  - Performance metrics (e.g., accuracy, loss, error)

## Outputs
- Trained neural network model
- Training curves (loss and/or accuracy)
- Model evaluation results
- Interpretation of model behavior

## How to Run
1. Clone or download this repository.
2. Ensure the dataset is available at `data/dataset.csv`.
3. Open and run:
   - `notebooks/Training_a_Neural_Network.ipynb`

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn
- TensorFlow / Keras or PyTorch (as used in the notebook)

## Notes
Focus is on **model training and evaluation**, not hyperparameter optimization
or deployment. Results reflect the specific dataset and architecture used.
