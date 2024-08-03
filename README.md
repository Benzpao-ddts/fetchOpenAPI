# OpenAPI Paths and Methods Extractor

## Description

This script fetches the OpenAPI specification from a given URL and extracts the API paths and methods. The results are saved into an Excel file. The script can be configured to filter paths by a specific keyword using regular expressions or to extract all paths.

## Requirement
- Python 3.x
- `requests` library
- `openpyxl` library

## Installation

1. **Install Python**: Ensure you have Python installed on your computer. You can download it from [python.org](https://www.python.org/).

2. **Install Required Libraries**: Open your terminal or command prompt and run the following commands to install the necessary libraries:
   ```bash
   pip install requests
   pip install openpyxl

## Usage
**1. Edit the Configuration Settings:**

openapi_url: The URL to fetch the OpenAPI specification (default is https://petstore.swagger.io/v2/swagger.json).
use_keyword: Set to True to filter paths by a keyword, or False to extract all paths.
keyword: The keyword to filter paths if use_keyword is True.

**2. Run the Script:**
- Save the script as a .py file, for example, extract_paths.py.
- Open a terminal or command prompt, navigate to the directory where you saved the script, and run it:
    ```bash
    python extract_paths.py

**3. Output:**

The script will create an Excel file (output_with_path.xlsx) in the specified directory with the extracted paths and methods.# fetchOpenAPI
