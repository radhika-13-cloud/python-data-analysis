✈️ Flights Data Cleaning & Transformation Project – Python (Pandas,numpy)

📝 Project Description

This project focuses on cleaning and transforming a messy flight dataset using Python and Pandas.

The aim of the project is to simulate real-world data preprocessing, where data is often:

•	incomplete

•	inconsistent

•	noisy

•	incorrectly formatted

The core objective is end-to-end data cleaning and feature engineering, which is the most important step in real analytics projects.
________________________________________
🎯 Project Objectives

The primary objectives of this project are:

•	To clean raw messy flight data

•	To handle missing and invalid values

•	To standardize text and column formats

•	To detect and remove duplicates

•	To correct data types

•	To remove impossible values such as negative distance

•	To create new useful derived fields for analysis
________________________________________
🧩 Dataset Details

The dataset used in this project contains:

•	Flight date

•	Airline name

•	Origin airport

•	Destination airport

•	Departure delay

•	Arrival delay

•	Flight distance

•	Cancellation flag

•	Tail number

•	Remarks / status comments

The dataset intentionally includes real-world quality issues like:

•	missing values

•	inconsistent casing (e.g., lax vs LAX)

•	leading and trailing spaces

•	duplicate records

•	negative and zero distances

•	unrealistic delay values

•	null remarks and tail numbers

•	inconsistent airline names
________________________________________
🛠 Tools & Technologies Used

•	Python

•	Pandas

•	NumPy

•	Jupyter Notebook / VS Code
________________________________________
🧮 Data Cleaning & Transformation Steps

The following data preprocessing steps were performed:

✔️ 1. Data loading and inspection

•	imported CSV file

•	viewed sample records

•	checked dataset shape

•	identified null values

•	inspected datatypes
________________________________________
✔️ 2. Standardization of column names

•	converted all columns to lowercase

•	removed extra spaces

•	replaced spaces with underscores
________________________________________
✔️ 3. Duplicate handling

•	identified duplicate rows

•	removed duplicate records from dataset
________________________________________
✔️ 4. Missing value treatment

•	filled missing airline names with “Unknown”

•	replaced missing cancellation values with 0

•	filled missing delays with 0

•	replaced missing tail numbers with NA

•	missing remarks replaced with “No Remark”
________________________________________
✔️ 5. Data type corrections

•	converted flight date into datetime format

•	converted numerical columns into numeric datatype
________________________________________
✔️ 6. Text data cleaning

•	removed extra spaces

•	converted airport codes to uppercase

•	standardized airline names

•	trimmed and cleaned tail numbers
________________________________________
✔️ 7. Handling invalid and extreme values

•	removed negative or zero distances

•	removed unrealistic delay values

•	validated airport codes
________________________________________
✔️ 8. Feature engineering

New fields created:

•	total_delay

•	flight status → Cancelled / Completed

•	delay category such as:

o	On Time

o	Slight Delay

o	Heavy Delay
________________________________________
✔️ 9. Export of cleaned dataset

Final dataset stored as:

flights_cleaned_final.csv

