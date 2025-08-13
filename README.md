# Heart Disease Analysis

This project analyzes heart disease datasets using statistical tests, visualizations, and machine learning models.

## Dataset Preparation

1. **Download the datasets**  
   Ensure you have the following datasets saved locally:
   - `heart_disease_uci.csv`
   - `heart_attack_prediction_dataset.csv`

2. **Upload the datasets to Google Colab**  
   In Colab, run the following snippet to upload the files:
   ```python
   from google.colab import files
   uploaded = files.upload()
   ```
   Select both CSV files from your local machine.

## Running the Notebook

1. **Open the notebook in Google Colab**  
   - Upload the `heart_analysis.ipynb` file to Colab.
   - Alternatively, if the repository is on GitHub, open the notebook via the GitHub URL.

2. **Install the required dependencies**  
   Run the following command in a Colab cell:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute all cells**  
   Run the notebook from start to finish to perform:
   - Data loading & cleaning
   - Statistical analysis
   - Data visualizations
   - Machine learning model training & evaluation

## Requirements

The full list of dependencies is in `requirements.txt`.  
For convenience, here are the core libraries:
```
google
matplotlib
numpy
pandas
scipy
seaborn
sklearn
```

## Notes
- This notebook is designed for **Google Colab** and may require slight modifications for local execution.
- Ensure that both datasets are available in the notebook's working directory before running the analysis.
