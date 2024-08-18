# UiPath Document Understanding Project

![Document Understanding Workflow](https://uipath.com/cdn-cgi/image/width=732,format=auto/https:////images.ctfassets.net/5965pury2lcm/2YgUA2fMZMklSE6EVRewBr/7a1bdffd168b4a08f595d11befcafe6a/How-to-use-RPA-for-Invoice-Extraction-and-Processing.png)


## Overview

This project is designed to automate the processing of various documents using UiPath's Document Understanding framework. It covers the complete workflow from document digitization to data extraction and exporting results to Excel.

## Features

- **Document Digitization**: Converts scanned documents into machine-readable text.
- **Document Classification**: Automatically categorizes documents into predefined types.
- **Data Extraction**: Extracts relevant data from documents using both form-based and machine learning-based approaches.
- **Results Validation**: Ensures the accuracy and consistency of extracted data.
- **Export to Excel**: Saves the processed data in Excel format for easy analysis and reporting.

## Project Structure

- **Taxonomy**: Defines the data structure to be extracted from documents.
- **Digitize Documents**: Converts images and scanned PDFs into text.
- **Classification**: Classifies documents based on their content.
- **Data Extraction Scope**:
  - **Form Extractor**: Extracts data from documents with consistent formats.
  - **Machine Learning Extractor**: Handles extraction from documents with varying formats.
- **Validation**: Reviews and validates the extracted data.
- **Export**: Exports the final data into an Excel spreadsheet.

## Installation

To run this project, you'll need:

- **UiPath Studio** with the following packages installed:
  - `UiPath.DocumentUnderstanding`
  - `UiPath.MachineLearningExtractor`
  - `UiPath.Excel.Activities`
  
1. Clone this repository to your local machine.
2. Open the project in UiPath Studio.
3. Install the required dependencies using the Manage Packages tool.

## Usage

1. **Define Taxonomy**: Customize the taxonomy to fit the specific document types you will be processing.
2. **Add Documents**: Place the documents you want to process in the designated input folder.
3. **Run the Automation**: Execute the workflow in UiPath Studio.
4. **Review Results**: Check the extracted data in the Excel output file.

## Customization

- **Adding New Document Types**: Modify the taxonomy and retrain the classification model to handle new types of documents.
- **Enhancing Data Extraction**: Customize the extraction rules or integrate additional extractors for specific data fields.

## Contributions

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

