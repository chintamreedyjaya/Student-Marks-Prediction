# Student Prediction Project

This repository contains datasets and Jupyter notebooks for experimenting with student performance prediction.

## Files in this Repo
- **student_prediction_dataset.csv**  
  Original dataset (base data).

- **student_prediction_dataset_1500_new.csv**  
  Expanded dataset with 1500 rows, created by repeating the pattern of the original dataset.

- **400&300.ipynb**  
  Notebook for training and testing models on the **original dataset** (`student_prediction_dataset.csv`).  
  Focused on subsets of 400 and 300 records.

- **accuracy with(1500).ipynb**  
  Notebook for training and testing models on the **expanded dataset** (`student_prediction_dataset_1500_new.csv`).  
  Used to check accuracy with the full 1500 rows.

## How It Works
1. Start with the **original dataset** (`student_prediction_dataset.csv`).
2. Expand it to **1500 rows** by repeating the same pattern.
3. Run the notebooks:
   - Use `400&300.ipynb` for smaller dataset experiments.
   - Use `accuracy with(1500).ipynb` for full 1500-row experiments.
