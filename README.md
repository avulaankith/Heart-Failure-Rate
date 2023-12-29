# Heart Failure Rate Prediction with PyTorch

This repository contains code and a dataset used for predicting heart failure rates using PyTorch. The dataset utilized for this analysis is the ["Heart Failure Clinical Records Dataset"](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data) obtained from Kaggle. It encompasses various clinical features that are potentially indicative of heart health.

## Repository Contents:

- **heart_failure_clinical_records_dataset.csv**: The dataset used for training and evaluation purposes.
- **heart_rate.ipynb**: Jupyter Notebook containing the complete model implementation.
- **logreg_model_heart.h5**: Logistic regression model saved as an HDF5 file.
- **logreg_model_heart_all.h5**: Another version of the logistic regression model saved as an HDF5 file.
- **LICENSE**: Apache-2.0 license file.

## Usage:

1. Clone the repository:

    ```bash
    git clone https://github.com/avulaankith/Heart-Failure-Rate.git
    ```

<!-- 2. Install the required dependencies (assuming Python and pip are already installed):

    ```bash
    pip install -r requirements.txt
    ``` -->

2. Explore the code provided in the Jupyter Notebook `heart_rate.ipynb` to understand the model implementation and data analysis.

3. Utilize the saved models (`logreg_model_heart.h5` and `logreg_model_heart_all.h5`) for inference or further development.

## Dataset Information:

The dataset used in this project, "Heart Failure Clinical Records Dataset," comprises various clinical features that can be leveraged to predict heart failure rates. It contains fields such as age, anaemia, creatinine levels, diabetes status, ejection fraction, high blood pressure, platelets count, serum creatinine, serum sodium, sex, smoking status, and more.

## Model Information:

The predictive models in this repository are based on logistic regression. The models have been trained and saved for reference as HDF5 files (`logreg_model_heart.h5` and `logreg_model_heart_all.h5`). The Jupyter Notebook `heart_rate.ipynb` contains the complete implementation, including data preprocessing, model training, evaluation, and inference.

## License:

This project is licensed under the terms of the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Acknowledgments:

- Kaggle user [andrewmvd](https://www.kaggle.com/andrewmvd) for providing the Heart Failure Clinical Records Dataset.
