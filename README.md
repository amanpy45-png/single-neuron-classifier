Pass/Fail Predictor Using Single Neuron
Overview:

This project implements a single-neuron binary classifier in Python to predict whether a student will pass or fail based on their CGPA and hours studied. It demonstrates basic neural network concepts like forward propagation, sigmoid activation, and gradient descent training.
__________________________________________________________________________________________________________________________________________________________________

Dataset:
The dataset contains:

Name	CGPA	Hours Studied	Result
Aman	8.88	3	Pass
Rahul	5.76	2.5	Fail
Sohan	8.32	4	Pass
Mohan	9.76	6.5	Fail
Robin	7.65	7	Pass
Mohit	6.98	1.5	Fail

__________________________________________________________________________________________________________________________________________________________________

Features:

Inputs: CGPA, Hours Studied
Output: Probability of passing (0–1) and predicted class (Pass/Fail)

__________________________________________________________________________________________________________________________________________________________________

How It Works:

Initialization: Random weights and bias.
Forward Pass: Calculates z = w·x + b and applies sigmoid activation.
Loss Calculation: Binary cross-entropy loss.
Backpropagation: Computes gradients and updates weights using gradient descent.
Prediction: Outputs probability and class for new students.

__________________________________________________________________________________________________________________________________________________________________

Usage

Clone the repository: git clone https://github.com/amanpy45-png/single-neuron-classifier.git
cd passfail-predictor

Run the script: python passfail_predictor.py

Modify the new_student array to predict for different CGPA and study hours.

__________________________________________________________________________________________________________________________________________________________________

Requirements:

Python 3.x
NumPy
Pandas
Matplotlib (optional, for visualization)

Install dependencies using: pip install numpy pandas matplotlib

__________________________________________________________________________________________________________________________________________________________________

Example Output:

Predicted probability: 0.73
Predicted class: Pass

__________________________________________________________________________________________________________________________________________________________________

Notes:

Small dataset is used for demonstration purposes.
This is a single-neuron model, not suitable for complex real-world datasets.
Can be extended to multi-layer neural networks.

__________________________________________________________________________________________________________________________________________________________________

License:
MIT License
