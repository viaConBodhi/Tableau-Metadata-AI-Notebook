# Tableau-Metadata-AI-Notebook
This project provides a comprehensive solution for working with Tableau’s metadata using Python and generative AI models. The notebook leverages Tableau’s REST and Document APIs to extract details from Tableau Server, parse Tableau workbook metadata, and utilize OpenAI’s GPT models to generate insightful descriptions of workbooks, dashboards, and data sources. This project aims to automate metadata documentation and make it accessible to both technical and non-technical users.

## Key Features:
- **Tableau API Integration**: Connect to Tableau Server to retrieve details about workbooks, datasources, and fields.
- **Metadata Parsing**: Extract and parse Tableau workbook XML metadata for further processing.
- **AI-Powered Documentation**: Utilize OpenAI’s GPT models to generate user-friendly summaries and documentation for Tableau workbooks, dashboards, and views.
- **Support for Large Metadata**: The code is optimized to handle up to 100k tokens, allowing for processing large and complex metadata sets.

## Requirements:
- Tested using python 3.9
- OpenAI API key (for accessing GPT models).
- Optional: Tableau Server credentials for interacting with Tableau’s API.

## Sections in the Notebook:
1. **Prerequisites**: Set up instructions and necessary API keys.
2. **API Connection Testing**: Verify your connections to OpenAI and Tableau Server.
3. **Data Extraction & AI Processing**: Walkthrough for extracting metadata and using AI to generate descriptions.

This notebook is ideal for data analysts, Tableau administrators, and anyone looking to automate Tableau metadata extraction and documentation processes.
