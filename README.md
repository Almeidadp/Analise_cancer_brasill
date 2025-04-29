# Cancer Datasets Analysis

## Installation

To use this project, you'll need to have the following dependencies installed:

- Python 3.13
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

The main script `datasets_cancer_global.py` performs the following tasks:

1. Loads the dataset `global_cancer_patients_2015_2024.csv`.
2. Explores the dataset by displaying basic information, handling missing values, and converting data types.
3. Analyzes the distribution of cancer types, patient ages, and cancer cases in Brazil.
4. Cleans and encodes the data for machine learning models.
5. Investigates four hypotheses related to cancer in Brazil:
   - Hypothesis 1: Cancer is increasing among young adults aged 20-30 years.
   - Hypothesis 2: Skin cancer is more common in men than in women.
   - Hypothesis 3: The survival rate for lung cancer is higher than for skin cancer.
   - Hypothesis 4: Women have higher cancer stages compared to men.

## API

This project does not provide a public API. It is a data analysis script that can be used as a reference or starting point for further cancer research and analysis.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

This project does not include any automated tests. The analysis is performed through exploratory data visualization and hypothesis testing.
