
# 🧠 MultiClass Classifier Network

This project involves developing a deep learning-based neural network model for multi-class classification tasks. The model is implemented using Python in a Jupyter Notebook environment and includes data preprocessing, model architecture design, training, and performance evaluation.

## 🚀 Project Overview

- **Goal**: To build a neural network model that can classify data across multiple categories with high accuracy.
- **Technologies Used**: 
   - Python
   - Jupyter Notebook
   - NumPy
   - Pandas
   - Scikit-learn
   - Matplotlib
   - Seaborn
- **Project Files**:
  - `MultiClass-Classifier-Network.ipynb`: Main Jupyter Notebook with full implementation.
  - `Rapor.pdf`: Detailed report describing project workflow and results.
  - `README.md`: This readme file.

## 📁 Dataset Used

The project uses a subset of the [CIFAR-100 dataset](https://www.cs.toronto.edu/~kriz/cifar.html), focusing on 6 specific classes:

- Beaver
- Boy
- Forest
- Oak Tree
- Snail
- Sunflower

These classes were selected to test the model’s ability to distinguish between multiple categories effectively.

## 🧠 Model Architecture

The model is a Multi-Layer Perceptron (MLP) neural network consisting of:

- **Input Layer**: Receives input features from the dataset.
- **Hidden Layers**: One or more layers with ReLU activation functions to capture complex patterns.
- **Output Layer**: Uses softmax activation to output class probabilities.

Compiled with `categorical_crossentropy` loss and `adam` optimizer for efficient training.

## 🛠️ Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MehmetOguzOzkan/MultiClass-Classifier-Network.git
   cd MultiClass-Classifier-Network
   ```

2. **Install Required Libraries**:
   ```bash
   pip install -r requirements.txt
   ```
   If the `requirements.txt` is missing, install manually:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```

3. **Run the Notebook**:
   ```bash
   jupyter notebook
   ```
   Open `MultiClass-Classifier-Network.ipynb` and run the cells step by step.

## 📊 Model Features

- **Data Preprocessing**: Checks for missing values, normalization, and splitting into training and test sets.
- **Architecture**: MLP structure with adjustable layers and neurons.
- **Training**: Optimized using Adam optimizer and monitored with accuracy metrics.
- **Evaluation**: Confusion matrix and classification report used to evaluate performance.

## 📈 Results

The model achieved high accuracy on the test dataset, successfully distinguishing between the selected classes. For visual results and performance details, refer to `Rapor.pdf`.

## 🤝 Contributing

Feel free to contribute by opening issues or submitting pull requests.

---

*This README is designed to clearly explain the purpose and usage of the project for other developers and users.*
