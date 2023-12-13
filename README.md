# Influenza-like illness in the United State Of America | Big Data Analytics

Welcome to the Influenza-like Illness Analytics System, a powerful tool designed to analyze and visualize data related to Influenza-like Illness (ILI) in the United States of America through the lens of Big Data Analytics. This sophisticated system provides valuable insights into the prevalence, trends, and predictions surrounding ILI, leveraging a data-driven approach to enhance our understanding of this public health concern.

link: https://jessieconnralphsam.github.io/usa_influenza_analytics/

**Overview**

The Influenza-like Illness (ILI) dataset provides information on reported cases of ILI across different regions, focusing on key metrics such as patient visits, ILI counts, and percentages. This documentation aims to guide users through understanding the structure and attributes of the dataset.

**Dataset Attributes**

**Index**

Description: A unique identifier for each record in the dataset.

Data Type: Integer

**Release_Week**

Description: The week during which the data was released.
Data Type: Integer

**Region**

Description: The geographical region for which ILI data is reported.

Data Type: Categorical (String)

**Week**

Description: The specific week during which ILI data was recorded.

Data Type: Integer

**Sites_Reporting**

Description: The number of reporting sites contributing data for the specified week.

Data Type: Integer

**Total_Patient_Visits**

Description: The total number of patient visits reported for the given week.

Data Type: Integer

**Total_ILI**

Description: The total count of Influenza-like Illness cases for the specified week.

Data Type: Integer

**Perc_Unweighted_ILI**

Description: The percentage of Unweighted ILI cases, representing the proportion of ILI cases to total patient visits.

Data Type: Float

**Perc_Weighted_ILI**

Description: The percentage of Weighted ILI cases, considering a weighted factor for more accurate representation.

Data Type: Float

**Sample Records**

| Index | Release_Week | Region   | Week   | Sites_Reporting | Total_Patient_Visits | Total_ILI | Perc_Unweighted_ILI | Perc_Weighted_ILI |
|-------|--------------|----------|--------|------------------|----------------------|-----------|----------------------|-------------------|
| 0     | 949          | Region 1 | 200935 | 96               | 64093                | 257       | 0.401                | 0.62755           |
| 1     | 949          | Region 1 | 200936 | 96               | 53552                | 265       | 0.4948               | 0.83766           |
| 2     | 949          | Region 1 | 200937 | 99               | 73590                | 478       | 0.6495               | 1.04911           |
| 3     | 949          | Region 1 | 200938 | 101              | 76099                | 622       | 0.8174               | 1.06889           |
| 4     | 949          | Region 1 | 200939 | 102              | 73743                | 614       | 0.8326               | 1.16454           |
| 5     | 949          | Region 1 | 200940 | 131              | 39576                | 664       | 1.6778               | 1.67598           |



**Note:**
The dataset is organized chronologically based on the release week.
Users are encouraged to refer to the README file for additional context and any updates related to the dataset.
For more information on the calculation of some attributes.

## Table of Contents

- [Installation](#installation)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [Credits](#credits)
- [FAQ](#faq)

## Installation
To install and run the Influenza-like Illness Analytics System locally, follow these steps:

1. Clone the repository to your local machine:

- git clone https://github.com/jessieconnralphsam/usa_influenza_analytics

2. Navigate to the project directory:

- cd usa_influenza_analytics

3. Open the project in your preferred code editor.

4. Run the system by opening your web browser's `index.html` file.

## Requirements
Ensure you have the following prerequisites installed:

- Web browser (Microsoft Edge, Google Chrome, Mozilla Firefox, etc.)
- Big Data of Influenza-like Illness in USA
## Usage
Loading Data:

- Click on the "Load Data" button to load specific data stored in a spreadsheet.

Information Map:

- Hover the map to view the region and state names. Clicking on a region will display specific data for that region.

Data Cleansing Summary:

 - View the data cleansing summary, including original data count, rows with missing values, data removed due to duplication, and clean data count.

Graphs and Predictions:

- Explore various graphs, such as "Average Regional Patient Visit vs Total ILI Cases per Region," and make predictions using the "Predictions" section.

## Contributing
If you'd like to contribute to the project, please follow these steps:

a. Fork the repository.

b. Create a new branch for your feature or bug fix.

c. Make your changes and submit a pull request.

## Credits
This system relies on data published by the Centers for Disease Control and Prevention (CDC).
## FAQ
Q: How often is the data updated in the system?<br>
A: The data is typically updated based on the Centers for Disease Control and Prevention (CDC) release schedule. Check the system regularly for the latest available information. <br>
Q: Is it possible to use my own dataset with the system?<br>
A: The Influenza-like Illness Analytics System is primarily designed to analyze and visualize data related to Influenza-like Illness (ILI). While the system is specialized for ILI analytics, you may still have the option to explore using your dataset. However, using datasets related explicitly to influenza-like illness is recommended for optimal results and accurate and meaningful insights. Please ensure that your dataset aligns with the intended purpose of the system. <br>

Q: How accurate are the predictions in the "Predictions" section?<br>
A: The accuracy of predictions depends on the quality and relevance of the training data. Make sure the training data accurate and relevant information for more reliable predictions.<br>
Q: I found a bug. How can I report it?<br>
A: Please report any bugs or issues by creating a new issue in the GitHub repository. Be sure to provide detailed information about the problem and steps to reproduce it.<br>
Q: Is there a user guide available for the system?<br>
A: Yes, you can find the documentation section in the README file for guidance on installation, usage, and contributing to the project.
Q: Can I contribute to the development of the system?<br>
A: Absolutely! We welcome contributions. Follow the steps outlined in the "Contributing" section of the README to fork the repository, create a new branch, make your changes, and submit a pull request.<br>
Feel free to customize these questions and answers based on the specific features and aspects of your Influenza-like Illness Analytics System.

