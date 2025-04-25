# Synthetic Data Generation for Stacking Model

## Why Synthetic Data?

- **Real data not yet available**: Base model predictions are still in development
- **Parallel development**: Allows building the stacking architecture without waiting
- **Early testing**: Validate the pipeline and resolve issues before using real data

## Characteristics of Generated Data

- Identical format to expected data (ticker, quarter_year, actual values, predictions)
- Simulation of realistic time trends and prediction errors
- 100 rows covering 5 companies over 5 years to facilitate testing

## Usage

Replace the `stacking_data_expanded_small.csv` file with real data when it becomes available, without having to modify the stacking model code.