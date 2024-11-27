# PDF-Table-Extractor
This project extracts table details from multiple PDF files, including their coordinates and structure (rows and columns), and saves the results in JSON format. It also visually highlights the detected tables on the original images by drawing borders around them.

# Prerequisites
Python 3.x

camelot-py

PyPDF2

Pillow

# Installation
Clone the Repository

     git clone <repository_url> 
     cd <repository_directory>

Install the Required Libraries

     pip install camelot-py[cv] PyPDF2 Pillow

# Usage
1. Prepare Your Directories

     Create an input folder with your PDF files.

     Create two output folders for the extracted JSON files and the detailed JSON files.

2. Update the Script
Open the script file and set the folder paths:

   input_folder = "path/to/your/input_folder"
   json_folder = "path/to/your/json_folder"
   details_folder = "path/to/your/details_folder"

3. Run the Script
Execute the script to process the PDFs and save the table details:
     python script_name.py
