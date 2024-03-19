# Titanic - Machine Learning from Disaster

This project tackles the Kaggle Titanic competition, which involves predicting the survival outcome of passengers aboard the Titanic based on various features such as age, gender, ticket class, etc.

## Dataset

The dataset for this project consists of two CSV files:

- `train.csv`: The training set containing the features and the target variable (Survived).
- `test.csv`: The test set containing only the features.

Both files can be downloaded from the Kaggle competition website: [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data).

## Dependencies

The following dependencies are required to run the code:

- Python 3
- pandas
- numpy
- scikit-learn

You can install the required dependencies using pip:
`pip install pandas numpy scikit-learn`

## Usage

1. Download the dataset files (`train.csv` and `test.csv`) from the Kaggle competition website. I have included the 3 files in my code repository.
2. Place the dataset files in the same directory as the Jupyter Notebook.
3. Open the Jupyter Notebook (`titanic_ml.ipynb`) in Jupyter Notebook or JupyterLab.
4. Run the notebook cells to execute the code step-by-step.
5. The notebook will train a Random Forest Classifier on the training data, make predictions on the validation set, and generate a submission file for the test set.
6. The final submission file (`submission.csv`) will be saved in the same directory.

## License

The code in this repository is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project is based on the Kaggle Titanic competition and utilizes the Titanic dataset provided by Kaggle.

For more information about the competition, dataset, and evaluation metrics, please refer to the [Kaggle Titanic competition page](https://www.kaggle.com/c/titanic).
