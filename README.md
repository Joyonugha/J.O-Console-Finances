# Financial Record Analysis Tool

This repository contains a JavaScript tool designed to analyze financial records, specifically focusing on Profit/Losses over a given period. The analysis is based on a dataset composed of arrays with two fields: Date and Profit/Losses. This README also provides a clear and concise guide to using your financial record analysis tool, making it easy for users to understand the project's purpose, how to set it up, and what to expect from the analysis.

# Project Overview
The tool calculates several key financial metrics from the dataset:

* Total Months: The total number of months included in the dataset.
* Net Total Profit/Losses: The net total amount of Profit/Losses over the entire period.
* Average Change in Profit/Losses: The average of the changes in Profit/Losses over the entire period, calculated as Total/(Number of months - 1).
* Greatest Increase in Profit/Losses: The date and the difference in the amounts for the greatest increase in Profit/Losses over the entire period.
* Greatest Decrease in Profit/Losses: The date and the difference in the amounts for the greatest decrease in Profit/Losses over the entire period.

## Table of Contents

- [Getting Started](#getting-started)
- [Screenshots](#screenshots)
- [Usage](#usage)
- [Expected Output](#expected-output)
- [Contributing](#contributing)
- [License](#license)

## Screenshots

![Screenshot1](/images/Screenshot%202024-03-05%20at%2001.06.43.png)
![Screenshot2](/images/Screenshot%202024-03-05%20at%2001.06.34.png)

# Getting Started

* Clone the Repository: First, copy the starter files into your local Git repository.

* Prepare Your Dataset: Ensure your dataset is in the correct format, with arrays containing Date and Profit/Losses fields.

* Install Dependencies: If the project requires any external libraries, make sure to include them in your project and install them.

* Run the Analysis: Open the JavaScript file in a browser or a JavaScript runtime environment (e.g., Node.js) to run the analysis.


# Usage

After setting up the project, the running of the analysis can be done by executing the JavaScript file. The tool will process the dataset and output the calculated metrics in the browser's console or a specified output format.

# Expected Output

When you run the code in a browser, the resulting analysis should display the following: 

* Total number of months. 

* The net total amount of Profit/Losses. 

* The average change in Profit/Losses. 

* The dates and differences for the greatest increase and decrease in Profit/Losses.

* The output should be formatted clearly and concisely, making it easy for users to understand the financial insights derived from the dataset.

# Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, please feel free to submit a pull request or open an issue.

# License

This project is licensed under the MIT License. See the LICENSE file for details.