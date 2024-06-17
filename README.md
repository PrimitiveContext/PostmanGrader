Overview
    This script processes a Postman collection JSON file and extracts various details into CSV files. It organizes the extracted data into a new structure, counts variables and values, and generates a summary of the collection.

Features
    Parsing Postman Collection: Extracts request details including method, URL, headers, and body.
    Variable Extraction: Identifies variables used within the collection.
    Value Extraction: Counts occurrences of values across different categories.
    Summary Generation: Provides a summary of the collection's content, including the number of requests, unique values, and variables.

Usage
    python parse.py <postman_collection.json>

Output Directory
    Matrix: bodies.csv, headers.csv, hosts.csv, paths.csv, queries.csv, and variables.csv.
    Meta: requests.csv and values.csv.
    summary.txt

Requirements
    Python 3.x
    pandas
