# Python Assignment 1

This repository contains solutions to multiple Python programming
problems related to algorithms, numerical approximation, and number
theory. The implementations are written in Python and demonstrated using
a Jupyter Notebook.

## Repository Contents

-   `2025BSDSAI059_OM PRATAP SINGH_Python Assignment_1.ipynb`\
    Jupyter Notebook containing all Python implementations and
    explanations.

------------------------------------------------------------------------

## Problems Implemented

### 1. Euclid's Algorithm (GCD)

Euclid's Algorithm is used to compute the **Greatest Common Divisor
(GCD)** of two integers.

**Function**

``` python
gcd(m, n)
```

**Description** - Takes two integers as input - Uses Euclid's algorithm
to compute their GCD - Handles negative numbers using `abs()`

------------------------------------------------------------------------

### 2. Approximating Euler's Number (e)

Two different methods are implemented to approximate the value of
Euler's number.

#### Method 1: Limit Definition

``` python
euler_limit(n)
```

Uses the formula:

e = (1 + 1/n)\^n

Large values of `n` may cause floating‑point precision issues in Python.

------------------------------------------------------------------------

#### Method 2: Series Expansion

``` python
euler_sum(n)
```

Uses the mathematical series:

e = Σ (1 / k!)

This method approximates `e` using the first `n` terms of the series.

------------------------------------------------------------------------

#### Adaptive Approximation

``` python
euler_approx(epsilon)
```

This function keeps adding terms until the approximation error becomes
smaller than a chosen epsilon value.

------------------------------------------------------------------------

### 3. Integer Property Testing

#### Checking Power of 2

``` python
is_power_of_2(n)
```

Returns `True` if the number is a power of 2.

Example:

``` python
is_power_of_2(8)   # True
is_power_of_2(10)  # False
```

------------------------------------------------------------------------

#### General Power Function

``` python
is_power(b, n)
```

Checks whether:

n = b\^k

for some integer `k`.

Example:

``` python
is_power(3, 27)  # True
is_power(2, 20)  # False
```

------------------------------------------------------------------------

## Technologies Used

-   Python 3
-   Jupyter Notebook
-   Python `math` library

------------------------------------------------------------------------

## How to Run

1.  Clone the repository

git clone https://github.com/your-username/repository-name.git

2.  Navigate to the folder

cd repository-name

3.  Start Jupyter Notebook

jupyter notebook

Open the notebook and run the cells.

------------------------------------------------------------------------

## Author

**Om Pratap Singh**\
Data Science / Artificial Intelligence Student

