# Summer_Analytics
The resources for the project are linked below:
https://drive.google.com/drive/folders/1GHLdL9g3RBRcM7VmJMWX_uxIC4TXYKc2

**Logistic Regression Classifier for Cat Recognition with Neural Network Mindset**

This project implements a logistic regression classifier with a neural network mindset to recognize cats in images. The classifier is built using Python, leveraging popular libraries such as NumPy for scientific computing, matplotlib for plotting graphs, h5py for interacting with an H5 dataset, and PIL/scipy for image processing.

### Project Overview:

1. **Dataset Loading:**
   - Utilizes the `lr_utils` module to load a dataset containing cat and non-cat images.
   - Displays an example image and its corresponding label.

2. **Data Preprocessing:**
   - Reshapes and flattens the training and test sets.
   - Normalizes pixel values to a range between 0 and 1.

3. **Model Components:**
   - Implements key functions such as sigmoid activation, parameter initialization, forward and backward propagation, and optimization.

4. **Training the Model:**
   - Defines a logistic regression model using gradient descent optimization.
   - Prints and plots the cost during training to monitor convergence.

5. **Model Evaluation:**
   - Evaluates the trained model on both the training and test sets.
   - Displays accuracy metrics for performance evaluation.

6. **Hyperparameter Tuning:**
   - Explores the impact of different learning rates on model performance.
   - Plots the learning curve for each learning rate.

7. **Prediction:**
   - Demonstrates the model's prediction on a sample image.
