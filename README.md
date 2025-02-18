# Python Functions for DNA, Prime Numbers, and Square Roots

## Overview
This project includes three Python functions that perform operations in bioinformatics and mathematical computations. The functions demonstrate logical operations, efficiency, and iterative methods for solving problems related to DNA sequences, prime numbers, and square roots.

## Features
- **DNA Complement Generator**: Returns the complementary DNA strand with an option to reverse it.
- **Prime Number Checker**: Determines if a given number is prime using an efficient square root approach.
- **Square Root Estimation**: Implements Heron's method to approximate square roots with adjustable precision.

## Installation
To run the code, ensure you have Python installed on your system (Python 3.x recommended). You can clone this repository using:

```bash
git clone git@github.com:manseebhossain1/Python-Functions-for-DNA-Prime-Numbers-and-Square-Roots.git
```

## Usage
### 1. DNA Complement Generator
```python
from dna_utils import get_complement

dna_sequence = "ATCG"
print(get_complement(dna_sequence, reverse=True))  # Output: CGAT
```

### 2. Prime Number Checker
```python
from math_utils import is_prime

print(is_prime(29))  # Output: True
print(is_prime(10))  # Output: False
```

### 3. Square Root Estimation
```python
from math_utils import estimate_sqrt

print(estimate_sqrt(25))  # Output: 5.0
print(estimate_sqrt(10, tolerance=1e-6))  # Output: Approximate value
```

## File Structure
```
📂 Python-Functions-for-DNA-Prime-Numbers-and-Square-Roots
├── dna_utils.py          # Contains DNA sequence functions
├── math_utils.py         # Contains prime number and square root functions
├── tests/                # Unit tests for all functions
├── README.md             # Project documentation
└── requirements.txt      # Required dependencies (if any)
```

## Testing
To run tests, use:
```bash
python -m unittest discover tests
```

## License
This project is open-source and available under the MIT License.

## Author
**Manseeb Hossain**
