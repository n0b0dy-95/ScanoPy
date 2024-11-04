# ScaNoPy Utility Application
	*A Python application for data normalization and standardization.*

# Version:
	- 0.25

# Introduction to ScaNoPy

	ScaNoPy is a utility application designed to streamline the process of scaling data using normalization and standardization techniques. It works primarily with `.csv` files and features a user-friendly graphical interface (GUI) that simplifies data processing for users at any level.

# Features at a Glance

	- **Easy Data Import**: Load training and test datasets from CSV files.
	- **Data Scaling**: Perform normalization and standardization on your datasets.
	- **Customizable Operations**: Select the dependent column and apply scaling to the remaining features.
	- **Efficient Data Export**: Save the scaled datasets in CSV format.
	- **Intuitive GUI**: A simple interface designed for ease of use.

# Prerequisites

	Before you start using ScaNoPy, make sure you have the following installed:
		- Python 3.6 or newer
		- pandas library
		- tkinter library
		- scikit-learn library
		- openpyxl library

# Getting Started with ScaNoPy

	1. **Launch ScaNoPy**: Run the application to open the GUI.
	2. **Load Training Data**: Click 'Browse' to select the CSV file for your training data.
	3. **Load Test Data**: Similarly, click 'Browse' to load the test data CSV file.
	4. **Select Scaling Operation**: Use the dropdown menu to choose between 'Normalize Data' or 'Standardize Data'.
	5. **Enter Dependent Column**: Click the button to input the dependent column that should be excluded from scaling.
	6. **Run the Operation**: Click 'Run' to apply the selected scaling method to the data.
	7. **Save Processed Data**: After processing, save the scaled datasets to CSV files.

# Example Workflow

	1. **Load Data**: Select both the training and test datasets in CSV format.
	2. **Choose Scaling**: Select either normalization or standardization.
	3. **Input Dependent Column**: Specify which column should not be scaled.
	4. **Run Scaling**: Click 'Run' to perform the selected operation.
	5. **Save Data**: Save the processed (scaled) data for both training and test sets.

# About the Author

	This project was created by **SUVANKAR BANERJEE**. ScaNoPy aims to simplify data preprocessing for machine learning models and other applications requiring normalized or standardized datasets.

# License

	ScaNoPy is released under the MIT License, promoting open and collaborative software development.

# Acknowledgments

	A special thanks to the contributors and supporters who have helped make ScaNoPy possible. Your feedback and contributions are greatly appreciated.

# Folder Contents:
 - Use:
	- "ScanoPy_v0.25__exe__" for the standalone Windows executable

# Note:
 - Please check the Readme.md file carefully before using the tool.

 - This app is created using pyinstaller and auto-py-to-exe python libraries. For further details please visit:
	
	* https://pyinstaller.org/en/stable
	* https://pypi.org/project/auto-py-to-exe

