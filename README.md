# NumPy Practice Repository

This repository contains Jupyter Notebooks dedicated to mastering NumPy, a fundamental library for scientific computing in Python. The notebooks cover a wide range of topics from basic array manipulation to advanced mathematical and statistical operations.

## 📂 Notebooks Overview

### 1. Practice 1: Array Manipulation & Logic
The first notebook focuses on the foundations of creating, inspecting, and restructuring NumPy arrays.

* **Array Creation:**
    * Generating empty, full, zero-filled, and boolean arrays.
    * Creating boolean masks for filtering data.
* **Indexing & Filtering:**
    * Extracting specific elements (e.g., odd numbers) and filtering based on conditions (e.g., values between 5 and 10).
    * Replacing values using boolean indexing (both in-place and using copies).
    * Finding positions of matching elements between two arrays using `np.where`.
* **Set Operations:**
    * Finding common items (`np.intersect1d`) and removing specific items (`np.setdiff1d`) from arrays.
* **Reshaping & Stacking:**
    * Converting 1D arrays to 2D matrices using `reshape`.
    * Stacking arrays vertically (`np.vstack`) and horizontally (`np.hstack`).
    * Swapping and reversing specific rows and columns.
* **Randomness & Printing:**
    * Generating random decimal numbers with `np.random.uniform` and `np.random.random`.
    * Customizing output formatting using `np.set_printoptions` (controlling precision and threshold).

### 2. Practice 2: Mathematical & Statistical Operations
The second notebook focuses on performing mathematical computations, linear algebra, and statistical analysis.

* **Element-wise Arithmetic:**
    * Performing addition, subtraction, and multiplication on arrays.
    * Computing element-wise squares, square roots (`np.sqrt`), and natural logarithms (`np.log`).
* **Linear Algebra:**
    * Calculating the dot product for 1D vectors and matrix multiplication for 2D arrays using `np.dot`.
    * Computing the Euclidean distance between vectors using `np.linalg.norm`.
* **Statistical Analysis:**
    * Calculating aggregates such as sum, mean, minimum, and maximum values.
    * Performing column-wise and row-wise calculations (e.g., sum of columns, mean of rows).
    * Finding the index of maximum values (`np.argmax`) and calculating cumulative sums (`np.cumsum`).
* **Broadcasting & Manipulation:**
    * Broadcasting operations, such as adding a 1D array to a 2D matrix or multiplying by a column vector.
    * Limiting array values within a specific range using `np.clip`.
* **Data Preprocessing:**
    * **Normalization:** Standardizing data by subtracting the mean and dividing by the standard deviation.

## 🛠️ Requirements
* Python 3.x
* NumPy
