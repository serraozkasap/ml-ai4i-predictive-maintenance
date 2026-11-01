# Predicting machine failures by using AI4I 2020 dataset on Kaggle

Class: Machine Learning and Data Mining 
Machine Learning project, University of Bologna — Serra Özkasap

The notebook predicts whether a milling machine is going to fail, using its sensor readings (temperatures, rotational speed, torque, tool wear). It follows CRISP-DM: business understanding, data understanding, data preparation, modeling, evaluation and conclusions.

**Main result:** the final model is a random forest. On the test set it catches 57 of the 68 failures with 9 false alarms.

## How to run

1. Open `ai4i_predictive_maintenance.ipynb` in Google Colab.
2. Run all cells. The dataset is read directly from this repository, so no upload is needed.

Libraries are listed in `requirements.txt`.

## Files

- `ai4i_predictive_maintenance.ipynb` — the whole project, with comments for every step
- `predictive-maintenance-dataset-ai4i-2020.csv` — the dataset ([Kaggle](https://www.kaggle.com/datasets/stephanmatzka/predictive-maintenance-dataset-ai4i-2020))
- `Report/` — the paper and the presentation
- `requirements.txt` — libraries used
