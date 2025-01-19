# Topsis-Tanisha-102203340

This project implements the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method in Python, which is used for multi-criteria decision analysis. It provides a command-line tool for performing TOPSIS on a dataset, as well as the functionality to upload the Python package to PyPi.

## Features

- **TOPSIS Implementation**: A Python program that performs TOPSIS on the provided dataset.
- **Command-line Tool**: The program can be executed from the terminal with the required parameters.
- **PyPi Package**: The package is uploaded to PyPi for easy installation and use by others.

## Installation

To install the package, you can use `pip`:

```bash
pip install topsis-tanisha-102203340
```

# Alternatively, you can clone the repository and run the script locally.

# Usage
To use the TOPSIS method, run the following command:

```bash
python topsis.py <inputFile> <weights> <impacts> <outputFile>
```

# Parameters:
1. <inputFile>: The CSV file containing the decision matrix (with alternatives and criteria).
2. <weights>: A comma-separated list of weights assigned to each criterion. Example: 1,1,1,2,1
3. <impacts>: A comma-separated list of impacts for each criterion. Example: +, +, -, +, -
4. <outputFile>: The file where the results will be saved.
   
# Example:
```bash
python topsis.py data.csv "1,1,1,2,1" "+,+,-,+,-" result.csv
```

# Contributing
Feel free to fork this repository, make changes, and submit pull requests. Please make sure to follow the guidelines and maintain the structure of the code.

To contribute:

1. Fork the repository.
2. Clone your fork: git clone https://github.com/your-username/Topsis-Tanisha-102203340.git.
3. Create a new branch: git checkout -b feature-branch.
4. Make your changes.
5. Commit your changes: git commit -m "Description of changes".
6. Push to the branch: git push origin feature-branch.
7. Submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE.txt file for details.

# Author
Tanisha Ahuja (102203340)
