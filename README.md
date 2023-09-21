# Prediction-using-supervised-ML


---

# Predicting Percentage of Students based on Study Hours

This project is a simple data analysis and prediction task in Python. It uses a dataset containing information about the number of study hours of students and their corresponding percentages to build a predictive model.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to predict the percentage of marks that a student is expected to score based on the number of hours they studied. It demonstrates a simple linear regression analysis using Python libraries such as NumPy, pandas, and scikit-learn.

## Dataset

The dataset used in this project contains two columns:

- `Hours`: The number of hours a student studied.
- `Percentage`: The percentage of marks the student scored.

You can replace this dataset with your own data for real-world applications.

## Getting Started

### Prerequisites

Before you can run the code, ensure you have the following libraries installed:

- NumPy
- pandas
- scikit-learn
- matplotlib (for visualization, optional)

You can install them using pip:

```shell
pip install numpy pandas scikit-learn matplotlib
```

### Installation

1. Clone this repository:

```shell
git clone <repository-url>
```

2. Navigate to the project directory:

```shell
cd <project-directory>
```

## Usage

1. Replace the dataset in the code with your own data or use the provided dataset in the following format:

```python
data = {'Hours': [2.5, 5.1, 3.2, 8.5, 3.5, 1.5, 9.2, 5.5, 8.3, 2.7],
        'Percentage': [21, 47, 27, 75, 30, 20, 88, 60, 81, 25]}
```

2. Run the Python script:

```shell
python linear_regression.py
```

3. The code will train a linear regression model, make predictions, and display a scatter plot (optional) showing the data points and the regression line.

## Example

```python
# Example usage of the trained model
hours = 6.5
predicted_percentage = model.predict([[hours]])
print(f"A student who studies {hours} hours is expected to score {predicted_percentage[0]:.2f}%.")
```

This example predicts the percentage score for a student who studies 6.5 hours.

## Contributing

If you'd like to contribute to this project, please feel free to submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
