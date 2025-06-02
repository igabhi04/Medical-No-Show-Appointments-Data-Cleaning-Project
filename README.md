# Medical-No-Show-Appointments-Data-Cleaning-Project


This project focuses on cleaning and preparing the **Medical Appointment No Shows** dataset from Kaggle using Python (Pandas). The dataset contains information about patients and whether they showed up for their medical appointments.

## 📁 Dataset

- Source: [Kaggle Dataset]
- File used: `KaggleV2-May-2016.csv`

## 🛠 Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook / VS Code / Google Colab

## ✅ Tasks Performed

1. **Load the Dataset**
   - Read the CSV file using `pandas.read_csv()`

2. **Handle Missing Values**
   - Checked for missing data using `.isnull().sum()`
   - Verified data completeness (this dataset has no missing values)

3. **Remove Duplicate Records**
   - Removed exact duplicate rows using `.drop_duplicates()`

4. **Standardize Text Values**
   - Fixed inconsistent entries in the `Gender`, `No-show`, and `Neighbourhood` columns
   - Example: Replaced `"F"` / `"M"` with `"Female"` / `"Male"`

5. **Date Formatting**
   - Converted `ScheduledDay` and `AppointmentDay` columns to `datetime` format
   - Standardized the format to `dd-mm-yyyy`

6. **Column Renaming**
   - Made all column headers lowercase, replaced spaces with underscores, and removed special characters

7. **Data Type Fixes**
   - Converted `age` to integer
   - Converted dates to `datetime64[ns]`

## 📊 Cleaned Dataset Output

After cleaning, the dataset is ready for use in further analysis, visualization, or machine learning tasks.



