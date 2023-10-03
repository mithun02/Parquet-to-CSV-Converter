# Parquet-to-CSV-Converter

This Python script converts a Parquet file to a CSV file using the Pandas library. This can be useful when you need to work with data in a Parquet format but want to export it to a more common CSV format for analysis or sharing.

# Getting Started
# Prerequisites
Before running the script, ensure you have the following prerequisites installed:

Python 3.x
Pandas library (can be installed via pip install pandas)
# Usage
Clone the repository to your local machine:

git clone https://github.com/yourusername/parquet-to-csv-converter.git

Navigate to the project directory:
cd parquet-to-csv-converter

Place your Parquet file (train-00000-of-00001-a09b74b3ef9c3b56.parquet) in the project directory.

# Run the script:

python parquet_to_csv.py

This will convert the Parquet file to a CSV file named output.csv in the same directory.

You can now find your converted CSV file in the project directory.

# Configuration

You can change the input and output file names by modifying the parquet_to_csv.py script:

# Input Parquet file
parquet_file = 'train-00000-of-00001-a09b74b3ef9c3b56.parquet'

# Output CSV file
csv_file = 'output.csv'

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments

Thanks to the Pandas library for providing the functionality to work with Parquet files and CSV files.











