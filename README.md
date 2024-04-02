# Data Analytics Project

## Overview

This repository contains the source code and necessary libraries for a data analytics project focused on classifying NLOS (Non-Line-of-Sight) and LOS (Line-of-Sight) signals in Ultra-Wideband (UWB) communications. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization.

## Installation

To run the project, you'll need Python installed on your system. Additionally, you'll need to install the required libraries using the following command:

```bash
pip install pandas numpy scipy scikit-learn matplotlib plotly seaborn
```

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/data-analytics-project.git
```

2. Navigate to the project directory:

```bash
cd data-analytics-project
```

3. Run the Python scripts provided to execute the project. For example:

```bash
python data_preprocessing.py
python exploratory_data_analysis.py
python feature_engineering.py
python model_training.py
python evaluation.py
python visualization.py
```

## Project Structure

- **data.py**: .
- **exploratory_data_analysis.py**: Original Dataset.
- **feature_engineering.py**: Combined Dataset.

## Dataset

The dataset used in this project includes the following features:

- Range
- FP_IDX: Index of detected first path element in channel impulse response (CIR) accumulator
- FP_AMP1: Amplitude of first harmonic in FP signal 
- FP_AMP2: Amplitude of second harmonic in FP signal
- FP_AMP3: Amplitude of third harmonic in FP signal
- CIR_PWR: Amplitude of channel impulse response
- RXPACC: Preamble accumulation count 
- Threshold: Difference between FP and RX level
- STDEV: Standard Deviation of Noise
- MAX_NOISE: Maximum Noise 
- Kurtosis: Kurtosis of CIR values
- 8 Sets of CIR values

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
