# Fictitious Names Data Analysis

This project involves the manipulation and merging of fictitious names data using Python and the Pandas library. The dataset includes information about subjects, their first names, last names, and test IDs.

## Project Overview

This repository contains Python code for analyzing fictitious names data using the Pandas library. The analysis includes steps to create and manipulate three DataFrames, perform different types of merging and concatenation, and combine data based on specific conditions. The primary goals of this project are:

- Create three DataFrames (data1, data2, data3) based on provided raw data.
- Join two DataFrames along rows and assign to all_data.
- Join two DataFrames along columns and assign to all_data_col.
- Print the contents of data3.
- Merge all_data and data3 based on the 'subject_id' value.
- Merge only the data that has the same 'subject_id' on both data1 and data2.
- Merge all values in data1 and data2, considering matching records from both sides where available.

## Analysis Steps

1. Import the required libraries, including Pandas and NumPy.
2. Create three DataFrames (data1, data2, data3) based on provided raw data.
3. Join two DataFrames along rows and assign the result to all_data.
4. Join two DataFrames along columns and assign the result to all_data_col.
5. Print the contents of data3.
6. Merge all_data and data3 based on the 'subject_id' value using an inner join.
7. Merge only the data that has the same 'subject_id' on both data1 and data2 using an inner join.
8. Merge all values in data1 and data2, considering matching records from both sides where available, using an outer join.

## Repository Structure

```
Fictitious-Names-Data-Analysis/
│
├── fictitious_names_analysis.ipynb  # Jupyter Notebook containing analysis code
└── readme.md                        # Project overview and details
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/Fictitious-Names-Data-Analysis.git`
2. Navigate to the repository: `cd Fictitious-Names-Data-Analysis`
3. Open the `fictitious_names_analysis.ipynb` notebook to access the detailed analysis steps and results.

## Acknowledgments

- Special thanks to Chris Albon for sharing the fictitious names dataset and materials for this analysis.
- Appreciation to the creators and contributors of the Pandas and NumPy libraries for empowering data manipulation and analysis.

