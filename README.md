
# Text Classification with SVM

Welcome to the Text Classification with SVM project! 🎉 This project demonstrates how to classify textual data using Support Vector Machines (SVM). We’ll clean and preprocess the data, vectorize it, and then train a model to predict responses based on user descriptions.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)

## Overview

In this project, we use a dataset containing user descriptions and their corresponding responses. The goal is to predict whether a user will respond based on their description. 

The main steps involved are:
1. Data cleaning and preprocessing.
2. Text vectorization using `CountVectorizer`.
3. Training a Support Vector Machine model.
4. Evaluating the model's performance using accuracy and a confusion matrix.

## Installation

To get started, make sure you have Python & Jupiter Notebook installed on your machine. You’ll also need to install the following libraries:

- `pandas`
- `scikit-learn`
- `seaborn`
- `matplotlib`

You can easily install these libraries using pip:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

## Usage

1. **Clone the Repository**:
   Start by cloning this repository to your local machine:
   ```bash
   git clone https://github.com/akshay-092/text-classification-svm.git
   ```

2. **Navigate into the Project Directory**:
   Change your directory to the project folder:
   ```bash
   cd text-classification-svm
   ```

3. **Prepare the Data**:
   Make sure you have the dataset file named `train.csv` in the project directory. This file should contain the relevant columns for the analysis.

## Data

This project uses a CSV file (`train.csv`) with the following relevant columns:

- `User_ID`: Unique identifier for each user (not used in the model).
- `Browser_Used`: Information about the user's browser (not used in the model).
- `Device_Used`: Information about the user's device (not used in the model).
- `Description`: The text data that we’ll classify.
- `Is_Response`: The target variable indicating whether a response was given (1 for yes, 0 for no).

## Results

After running the script, you'll get:
- The accuracy score of the model.
- A confusion matrix visualized using a heatmap, helping you understand how well the model is performing.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

---

Thank you for checking out the project! If you have any questions or feedback, don’t hesitate to reach out. Happy coding! 😊
```