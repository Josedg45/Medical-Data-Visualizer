# Medical Data Visualizer

This project visualizes and analyzes medical examination data using Python's pandas, seaborn, and matplotlib libraries. The dataset contains information about patients' body measurements, blood test results, and lifestyle choices, as well as whether they have cardiovascular disease.

## Data Description

- **Age**: Age of the patient in days
- **Height**: Height of the patient in centimeters
- **Weight**: Weight of the patient in kilograms
- **Gender**: Gender of the patient (categorical code)
- **Systolic blood pressure**: Systolic blood pressure of the patient
- **Diastolic blood pressure**: Diastolic blood pressure of the patient
- **Cholesterol**: Cholesterol level of the patient (1: normal, 2: above normal, 3: well above normal)
- **Glucose**: Glucose level of the patient (1: normal, 2: above normal, 3: well above normal)
- **Smoking**: Whether the patient smokes (binary)
- **Alcohol intake**: Whether the patient consumes alcohol (binary)
- **Physical activity**: Whether the patient is physically active (binary)
- **Presence or absence of cardiovascular disease**: Target variable (binary)

## Tasks

1. Add an 'overweight' column to the data.
2. Normalize the data by making 0 always good and 1 always bad for cholesterol and glucose.
3. Convert the data into long format and create a chart that shows the value counts of the categorical features split by the presence or absence of cardiovascular disease.
4. Clean the data by filtering out incorrect data segments.
5. Create a correlation matrix and plot it as a heatmap.

## File Description

- **medical_data_visualizer.py**: Python script containing functions to visualize and analyze the medical examination data.
- **medical_examination.csv**: CSV file containing the medical examination data.

## Usage

To use this project, make sure you have Python installed along with the pandas, seaborn, and matplotlib libraries. Run the `medical_data_visualizer.py` script to visualize and analyze the data.

```bash
python medical_data_visualizer.py
