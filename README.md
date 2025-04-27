# ML Pipeline for Classification

This repository contains a complete Machine Learning pipeline implemented in a Jupyter Notebook.  
The pipeline covers all critical stages — from data preprocessing to model evaluation — with a focus on **probability calibration** and **ensemble strategies**.

## Contents

- **Data Importing**: Load datasets and external JSON files.
- **Preprocessing**: Handle missing values, outliers, and data cleaning.
- **Feature Engineering**:
  - Feature generation (creating new meaningful features)
  - Feature reduction (dimensionality reduction techniques)
- **Train-Test Split**: Create training and validation datasets.
- **Probability Calibration**: Improve probability outputs of classifiers.
- **Model Selection**: Select suitable models based on performance.
- **Hyperparameter Tuning**: Optimize model parameters for better results.
- **Weighting Strategy**: Apply strategies to combine model outputs.
- **Model Prediction**: Generate predictions.
- **Evaluation**: Comprehensive model evaluation with appropriate metrics.

## Getting Started

### Prerequisites
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - joblib

You can install dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

### How to Run
1. Clone this repository.
2. Open the `Pipeline code 01.ipynb` notebook.
3. Follow the cells sequentially or run all at once.

```bash
jupyter notebook Pipeline\ code\ 01.ipynb
```

## Key Highlights

- **JSON Integration**: External parameters/configurations are imported from JSON files.
- **Probability Calibration**: Calibrating probabilities to make outputs more reliable.
- **Advanced Model Tuning**: Hyperparameter search strategies.
- **Ensemble Weighting**: Combine model outputs strategically for better performance.

## License

This project is licensed under the MIT License — feel free to use it for personal or commercial purposes.

## Acknowledgements

Thanks to all the open-source libraries and tools that made this project possible.
