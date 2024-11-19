# Newton Interpolation with Divided Differences and XOR-Based Labeling

This repository contains a project showcasing the application of Newton's interpolation method, combined with machine learning concepts like sigmoid activation and XOR-based labeling. The project demonstrates how numerical methods and basic machine learning principles intersect to solve practical problems.

## Overview

1. **Divided Differences**:
   - Efficient computation of the coefficients for Newton's interpolating polynomial.
   - These coefficients allow us to construct a polynomial that fits a given dataset.

2. **Newton's Polynomial**:
   - Interpolation method that builds a polynomial to approximate a given function.
   - Useful in numerical analysis and data fitting tasks.

3. **XOR-Based Labeling**:
   - Labels data points based on an XOR logic rule.
   - Serves as a simple classification problem for visualization and model evaluation.

4. **Machine Learning Integration**:
   - Uses a sigmoid activation function for binary classification.
   - Applies to XOR-labeled data to train and predict results.

---

## Code Files

### `diferencias_divididas.py`
- **Purpose**: Computes the coefficients for Newton's interpolation using divided differences.
- **Highlights**:
  - Efficient double-loop implementation for coefficient calculation.

### `newton_polynomial.py`
- **Purpose**: Evaluates the Newton interpolating polynomial using precomputed coefficients.
- **Highlights**:
  - Accumulates polynomial terms dynamically for accurate predictions.

### `xor_labeling.py`
- **Purpose**: Labels data points using an XOR logic for classification tasks.
- **Highlights**:
  - Generates labels (0 or 1) based on the relative position of points.

### `model_training.py`
- **Purpose**: Trains a binary classifier using sigmoid activation on XOR-labeled data.
- **Highlights**:
  - Predicts and rounds outputs for binary classification.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Dilanrojasca/BreadcrumbsNewton-Interpolation-with-Divided-Differences-and-XOR-Based-Labeling

   cd BreadcrumbsNewton-Interpolation-with-Divided-Differences-and-XOR-Based-Labeling

   ```

2. Install dependencies (if any):
   ```bash
   pip install -r requirements.txt
   ```

3. Run the scripts sequentially or as needed:
   - Calculate divided differences:
     ```bash
     python diferencias_divididas.py
     ```
   - Evaluate the polynomial:
     ```bash
     python newton_polynomial.py
     ```
   - Generate XOR labels:
     ```bash
     python xor_labeling.py
     ```
   - Train the model and predict:
     ```bash
     python model_training.py
     ```

---

## Applications

- Numerical approximation and interpolation.
- Data fitting and curve approximation.
- Binary classification tasks using simple logic rules like XOR.
- Understanding the relationship between mathematical models and machine learning.

---

## Example Use Case
1. Use Newton's polynomial to interpolate data points from a control dataset.
2. Label the interpolated points using the XOR logic.
3. Train a simple machine learning model to classify the labeled data.
4. Evaluate model predictions against the original dataset.

---

## Contributions
Contributions are welcome! Feel free to fork the repo and submit pull requests.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
