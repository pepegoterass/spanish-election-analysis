# Spanish Elections Analysis

## Overview

This project develops comprehensive predictive models for Spanish municipal electoral data using classical statistical methods. The analysis encompasses complete data preprocessing, rigorous model development through Forward/Backward/Stepwise selection with AIC/BIC criteria, and thorough model validation.

**Dataset**: `DatosEleccionesEspaña.xlsx` - Spanish municipal electoral and demographic data (not included in repo due to size; download separately).

**Models Developed**:

- Linear Regression for continuous electoral outcomes
- Logistic Regression for binary electoral classification

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pepegoterass/spanish-election-analysis.git
   cd spanish-election-analysis
   ```

2. Install required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
   ```

3. Download the dataset `DatosEleccionesEspaña.xlsx` and place it in the project directory.

## Usage

1. Open the Jupyter notebook:

   ```bash
   jupyter notebook Data_Mining_Elections_Analysis.ipynb
   ```

2. Run the cells sequentially to reproduce the analysis, including data preprocessing, outlier detection, missing value handling, and model training/evaluation.

3. Key outputs include model summaries, performance metrics, and visualizations.

## Project Structure

- `Data_Mining_Elections_Analysis.ipynb`: Main notebook with complete analysis
- `DatosEleccionesEspaña.xlsx`: Dataset (external download required)
- `README.md`: This file

## AI Use

While developing this project, I utilized AI assistance (specifically, Grok by xAI) to identify and resolve data errors during preprocessing, optimize code efficiency, and ensure clear, accurate documentation and writing throughout the analysis. The AI helped in debugging code issues, suggesting improvements for data handling, and refining the narrative to maintain consistency and professionalism in the report.

## License

This project is for educational purposes. Please cite appropriately if used.

## Contact

For questions or contributions, open an issue on GitHub.
