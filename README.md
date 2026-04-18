# Netflix-data-cleaning-
Netflix Data Cleaning &amp; Preprocessing 🎬 This repository contains a Python-based data cleaning project focused on transforming a raw Netflix dataset into an analysis-ready format. The project utilizes Pandas and NumPy within a Jupyter Notebook environment to address common data quality issues such as placeholder values
📌 Project Overview
The goal of this project was to take a messy version of the Netflix titles dataset and perform a comprehensive cleaning "pipeline." This ensures that any subsequent Exploratory Data Analysis (EDA) or Machine Learning models are built on accurate, standardized information.

📊 Dataset Description
The original dataset (netflix1.csv) contained 8,790 rows and 10 columns, including:

show_id: Unique ID for every movie/TV show.

type: Identifier (Movie or TV Show).

title: Name of the content.

director: Director of the content.

country: Country where the movie/show was produced.

date_added: Date it was added to Netflix.

release_year: Actual release year.

rating: TV Rating (e.g., PG-13, TV-MA).

duration: Total length (minutes or seasons).

listed_in: Genres.

🛠️ Cleaning Steps Performed
I followed a systematic approach to sanitize the data:

Handling Placeholder Values: Identified that missing data was labeled as "Not Given" rather than null values. Replaced these with "Unknown" to maintain categorical integrity.

Date Standardization: Converted the date_added column from a string (object) format to a formal datetime object for time-series analysis.

Text Normalization: Applied .strip() to all string columns to remove accidental leading/trailing whitespaces that could cause duplicate categories.

Null & Duplicate Check: Verified that the dataset contained no duplicate rows and handled any remaining null values to ensure a 100% clean record set.

Feature Refining: Standardized the rating and type categories for consistency.

🚀 Technologies Used
Language: Python 3.x

Libraries: Pandas, NumPy

Environment: Google Colab / Jupyter Notebook

📁 Repository Structure
netflix_data_cleaning.ipynb: The complete Python script with step-by-step explanations.

netflix1.csv: The raw input data.

netflix_cleaned.csv: The final, processed dataset ready for visualization.

📈 Key Takeaways
By the end of this process, the dataset was reduced from a "messy" state to a high-quality asset:

Consistency: No hidden spaces or mixed naming conventions.

Usability: Dates are now functional for filtering by year/month.

Clarity: Missing directors and countries are properly categorized as "Unknown."

Tips for your GitHub:
Add a "Visuals" section: If you created any charts after cleaning, upload them to the repo and link them in the README.

License: Adding an MIT license makes your project look more official.
https://www.linkedin.com/in/mariam-yahia-0381312b8?
