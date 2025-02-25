# Audible Dataset Cleaning and Standardization Project

## Project Overview
This project focuses on cleaning and standardizing an Audible dataset using **Power Query Editor** in Excel. The aim is to ensure the dataset is consistent, formatted correctly, and ready for further analysis.

---

## Key Objectives

1. **Standardize the `name` column:**
   - Apply consistent title casing to ensure uniformity across all entries.

2. **Separate `author` names:**
   - Split combined first and last names into separate columns if currently merged.

3. **Normalize the `releasedate` column:**
   - Ensure all date entries follow a consistent format: `DD-MM-YYYY`.

4. **Convert the `time` column:**
   - Change the time values from text to a duration format that Excel recognizes.

5. **Format the `price` column:**
   - Ensure all price values are numeric.
   - Identify and address any non-numeric entries.
   - Apply consistent formatting with two decimal places.

6. **Convert `stars` column:**
   - Transform text-based ratings into numeric values.

7. **Split the `narratedby` column:**
   - If multiple narrators are listed, split their names into separate columns.

8. **Merge `releasedate` and `language`:**
   - Create a new column named `releaseinfo` with the format:  
     **`DD-MM-YYYY, Language`**

---

## Tools & Technologies
- **Microsoft Excel**
  - Power Query Editor
  - Data cleaning and transformation tools

---

## Steps Performed

### 1. Data Cleaning
- Standardized text formatting in the `name` column to **title case**.
- Ensured all entries in the `releasedate` column adhered to the format `DD-MM-YYYY`.

### 2. Column Transformations
- Split the `author` column into **First Name** and **Last Name** where required.
- Transformed the `time` column into Excel's **duration format**.

### 3. Data Formatting
- Converted `price` values to numeric format and ensured consistency with two decimal places.
- Validated and corrected non-numeric price entries.

### 4. Data Enrichment
- Transformed text-based `stars` into numeric ratings.
- Split the `narratedby` column into separate columns for multiple narrators.
- Created a new column `releaseinfo` by merging `releasedate` and `language` with the format:  
  **`DD-MM-YYYY, Language`**

---

## Results
- A cleaned and standardized dataset ready for analysis.
- Consistent formatting across all columns.
- Enhanced data usability for future projects and analytics.

---

## File Details
- **Original Dataset:** `audible_dataset_raw.xlsx`
- **Cleaned Dataset:** `audible_dataset_cleaned.xlsx`

---

## How to Use
1. Open the `audible_dataset_cleaned.xlsx` file in Excel.
2. The dataset is prepared for further analysis and can be directly used for:
   - Visualizations
   - Reporting
   - Advanced analytics

---

## Contributing
If you wish to contribute to this project:
1. Fork the repository.
2. Make your changes in a new branch.
3. Submit a pull request with a clear description of the changes.

---

## Acknowledgments
Special thanks to the **Excel Power Query community** for providing resources and tutorials on advanced data cleaning techniques.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
