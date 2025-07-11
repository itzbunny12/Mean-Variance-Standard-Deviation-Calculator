# Mean-Variance-Standard-Deviation-Calculator

A Python project that calculates mean, variance, and standard deviation from a 3×3 matrix using NumPy.

## Features

- Accepts a 3x3 matrix as input
- Calculates:
  - Mean
  - Variance
  - Standard deviation
- Uses the NumPy library for computations

## Installation

Clone the repository:
```bash
git clone https://github.com/itzbunny12/Mean-Variance-Standard-Deviation-Calculator.git
cd Mean-Variance-Standard-Deviation-Calculator
```

Install the required dependencies:
```bash
pip install numpy
```

## Usage

Replace the matrix in the script with your own 3x3 matrix or modify the code to accept user input.

```python
import numpy as np

matrix = np.array([[1,2,3],[4,5,6],[7,8,9]])

mean = np.mean(matrix)
variance = np.var(matrix)
std_deviation = np.std(matrix)

print("Mean:", mean)
print("Variance:", variance)
print("Standard Deviation:", std_deviation)
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
