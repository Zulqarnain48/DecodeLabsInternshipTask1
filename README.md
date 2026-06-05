# DecodeLabsInternshipTask1

# Data Cleaning & Preparation Project

## Project Overview
This project was completed as part of the DecodeLabs Data Analytics Industrial Training Program (Project 1). The main objective was to clean and prepare a raw dataset by identifying and handling missing values, removing duplicate records, correcting data inconsistencies, and ensuring proper formatting for analysis.

Data cleaning is one of the most important stages in the data analytics process because accurate analysis depends on high-quality and reliable data.

---

## Project Objective

The goal of this project was to:

- Identify and handle missing values
- Detect and remove duplicate records
- Correct incorrect or inconsistent data
- Standardize data formats
- Prepare the dataset for further analysis and visualization
- Improve overall data quality and reliability

---

## Dataset Information

The dataset contains customer order information from an e-commerce platform.

### Features Included

| Column Name | Description |
|------------|-------------|
| OrderID | Unique order identifier |
| Date | Order date |
| CustomerID | Unique customer identifier |
| Product | Product purchased |
| Quantity | Number of units ordered |
| UnitPrice | Price per unit |
| ShippingAddress | Customer shipping address |
| PaymentMethod | Method used for payment |
| OrderStatus | Current order status |
| TrackingNumber | Shipment tracking number |
| ItemsInCart | Total items in cart |
| CouponCode | Applied discount code |
| ReferralSource | Source of customer referral |
| TotalPrice | Total order amount |

---

## Data Cleaning Tasks Performed

### 1. Missing Value Handling

The dataset was examined for missing or null values.

Actions performed:

- Identified blank cells and missing entries.
- Replaced missing values where appropriate.
- Ensured important columns contained valid data.
- Verified that no critical fields remained empty.

---

### 2. Duplicate Record Removal

Duplicate records can lead to incorrect analysis.

Actions performed:

- Checked the dataset for duplicate rows.
- Identified repeated records.
- Removed duplicate entries.
- Verified dataset uniqueness after cleaning.

---

### 3. Data Format Standardization

Different data formats create inconsistencies during analysis.

Actions performed:

#### Date Formatting
- Converted dates into a consistent format.
- Removed invalid date entries.
- Ensured all dates followed the same standard.

#### Text Formatting
- Standardized text values.
- Removed unnecessary spaces.
- Corrected capitalization inconsistencies.

#### Numeric Formatting
- Verified numerical columns.
- Corrected invalid values.
- Ensured quantities and prices used proper numeric formats.

---

### 4. Data Validation

After cleaning, validation checks were performed:

- No duplicate Order IDs
- Consistent date formatting
- Proper numeric values
- Valid categorical values
- Clean and analysis-ready dataset

---

## Tools Used

### Microsoft Excel

The following Excel features were used:

- Filter
- Sort
- Find & Replace
- Remove Duplicates
- Conditional Formatting
- Data Validation

---

## Project Workflow

1. Load raw dataset
2. Inspect dataset structure
3. Identify missing values
4. Remove duplicates
5. Correct formatting issues
6. Validate cleaned data
7. Save cleaned dataset
8. Prepare dataset for analysis

---

## Final Output

The project produced a cleaned dataset that:

- Contains consistent records
- Has no duplicate entries
- Uses standardized formats
- Is ready for Exploratory Data Analysis (EDA)
- Can be used for visualization and reporting

---

## Learning Outcomes

Through this project, the following skills were developed:

- Data Cleaning
- Data Preparation
- Data Quality Assessment
- Excel Data Handling
- Missing Value Treatment
- Duplicate Detection
- Data Validation
- Analytical Thinking

---

## Files Included

### Raw Dataset
Original dataset before cleaning.

### Cleaned Dataset
`cleaned_dataset.csv`

Contains the cleaned and validated data ready for analysis.

### Project Documentation
Project instructions and requirements provided by DecodeLabs.

---

## Conclusion

Data cleaning is a critical step in the data analytics lifecycle. This project focused on transforming raw and potentially unreliable data into a clean, consistent, and analysis-ready dataset. By handling missing values, removing duplicates, correcting formatting issues, and validating the final output, the dataset became suitable for further analytical tasks such as Exploratory Data Analysis (EDA), visualization, and business reporting.

---

## Author

**Zunair Talpur**

Data Analytics Intern

DecodeLabs Industrial Training Program
