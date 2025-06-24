# Filesure Internship Take-Home Assignment

This project demonstrates the extraction of structured data and generation of summaries from a real-world regulatory PDF document (Form ADT-1). It also supports optional extraction of embedded attachments if present within the PDF.



## How to Run the Code

To successfully run the project, follow these three main steps. Each step corresponds to a dedicated script:

1. **Extract Data from PDF**  
   The first step involves running the extraction script. This script opens the PDF document, parses its content, and extracts all relevant information. The output is a structured JSON file containing key fields such as company details, auditor information, and appointment data.

2. **Generate Summary**  
   After extracting the data, run the summary generation script. This reads the structured JSON and produces a clear, concise, and professional summary of the auditor appointment and related details. The summary is saved as a plain text file for easy review and sharing.

3. **(Optional) Extract Attachments**  
   If the PDF includes any embedded attachments (such as additional supporting documents), the attachments handler script can be run to extract these files automatically. The extracted attachments will be saved into a dedicated folder.



## Overview

- Each step is designed to be run independently, allowing flexibility in processing.
- The code is modular, well-documented, and easy to maintain.
- This workflow automates the conversion of unstructured regulatory documents into structured data and readable summaries, improving efficiency and accuracy.



## Author

**Sumiya Tab**  
Email: sumiyahappy6@gmail.com  
GitHub: [https://github.com/sumiya120](https://github.com/sumiya120)




