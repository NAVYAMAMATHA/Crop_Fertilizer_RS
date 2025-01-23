# Crop and Fertilizer Recommendation System

This repository contains a machine learning project designed to recommend the most suitable crop and fertilizer based on specific soil and environmental conditions. By leveraging data analysis and machine learning, this project aims to optimize agricultural productivity.

## Features

- **Crop Recommendation**: Suggests the most suitable crop based on soil and weather parameters.
- **Fertilizer Recommendation**: Provides fertilizer suggestions tailored to the selected crop and soil deficiencies.
- **User-Friendly Interface**: Simplifies decision-making for farmers and agricultural professionals.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Dataset](#dataset)
4. [License](#license)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/NAVYAMAMATHA/crop-fertilizer-recommendation.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3.used the uploaded dataset(Crop_recommendation.csv) in DATASET folder.


---

## Usage

1. Ensure the dataset file (e.g., `data.csv`) is in the root directory.
2. Run the script for recommendations:
   ```bash
   python crop.py
   ```
3. Input the required parameters such as soil type, nitrogen, phosphorus, potassium levels, temperature, and humidity.
4. The system will output the recommended crop and fertilizer.

### Example Output:

```
Recommended Crop: Rice
Recommended Fertilizer: Urea
```

---

## Dataset

The dataset should include the following parameters:

| Column Name   | Description                               |
| ------------- | ----------------------------------------- |
| `N`           | Nitrogen content in the soil             |
| `P`           | Phosphorus content in the soil           |
| `K`           | Potassium content in the soil            |
| `temperature` | Temperature in degrees Celsius           |
| `humidity`    | Humidity percentage                      |
| `ph`          | pH value of the soil                     |
| `rainfall`    | Rainfall in mm                           |
| `label`       | The recommended crop (for crop dataset)  |

Datasets can be obtained from sources like [Kaggle](https://www.kaggle.com/) or custom agricultural data collections.
---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
