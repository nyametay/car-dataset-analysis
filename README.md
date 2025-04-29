🚗 Car Dataset Analysis
This repository contains a Jupyter Notebook that performs data cleaning, exploration, and filtering operations on a car dataset. The project demonstrates how to process real-world tabular data using Python and pandas.

📓 Notebook Overview
Car Notebook.ipynb includes:

Loading a CSV file of car specifications

Identifying and handling missing values

Value count analysis for categorical columns

Filtering data based on specific conditions

Creating new derived columns

🧾 Dataset Description
The dataset contains specifications of various cars including:

Make (car brand)

Cylinders

Weight

MPG_City

Origin (e.g., Asia, Europe)

Dataset used: Project+2+-+Cars+Dataset.csv (must be placed in the ../Datasets/ directory or update the path accordingly)

🧹 Data Cleaning Steps
Checked for and handled null values

Replaced missing values in the Cylinders column with the mean

Dropped completely empty rows

📊 Analysis Performed
Value Counts
Counted the occurrences of each car make using .value_counts().

Filtering
Displayed only cars originating from Asia or Europe.

Conditional Removal
Removed all cars with a weight over 4000.

Column Transformation
Created a new column MPG_City_ with all values increased by 3 from MPG_City.

🛠️ Requirements
Install necessary dependencies using:

bash
Copy
Edit
pip install pandas
Or if you're using Jupyter:

bash
Copy
Edit
pip install notebook pandas
🚀 Running the Notebook
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/car-dataset-analysis.git
cd car-dataset-analysis
Start Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Open Car Notebook.ipynb and run the cells to explore and analyze the dataset.
