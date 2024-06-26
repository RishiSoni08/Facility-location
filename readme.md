# Facility Location Problem

## Overview

This project addresses the **P-Median Facility Location Problem**. Given `n` demand locations, the objective is to determine the optimal placement of `m` facilities such that the total distance between demand points and facilities is minimized.

## Project Structure

1. **distance_matrix.csv**: This file contains the distance matrix, which is derived from location coordinates.
2. **location_coordinates.ipynb**: A script that converts location coordinates stored in a dictionary into a CSV file.
3. **p_median_facility_location_problem.ipynb**: A script to solve the P-Median problem, determining the optimal placement of facilities.

## Files

### distance_matrix.csv

- This CSV file includes the distance matrix, which is essential for solving the facility location problem. The matrix is created from the provided location coordinates.

### location_coordinates

- This script converts location coordinates from a dictionary format into a CSV file. The output CSV is then used to generate the distance matrix.

### p_median_facility_location_problem

- This script solves the P-Median Facility Location Problem. Given `n` demand locations, it determines which `m` facilities should be set up to minimize the total distance.

## Problem Statement

Given `n = 50` demand locations, determine the optimal placement of `m = 3` facilities. The goal is to minimize the total distance between the demand locations and the facilities.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/facility-location-problem.git
    cd facility-location-problem
    ```

2. Set up a virtual environment and install the required packages:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your location coordinates data in a dictionary format.
2. Convert the location coordinates to a CSV file:
    ```sh
    python location_coordinates.py
    ```
3. Solve the P-Median Facility Location Problem:
    ```sh
    python p_median_facility_location_problem.py
    ```

## Example

1. **Input Data (Dictionary format):**
    ```python
    location_dict = {
        "Location1": (lat1, lon1),
        "Location2": (lat2, lon2),
        ...
    }
    ```

2. **Convert to CSV:**
    ```sh
    python location_coordinates.py
    ```

4. **Solve the P-Median Problem:**
    ```sh
    python p_median_facility_location_problem.py
    ```

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss what you would like to change.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please contact [rishi25soni@gmail.com].

