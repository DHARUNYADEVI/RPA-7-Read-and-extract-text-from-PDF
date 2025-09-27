# RPA-7-Read-and-extract-text-from-PDF
## NAME:DHARUNYADEVI S
## REGISTER NUMBER:212223220018
# AIM:
To create a UiPath workflow that reads and extracts text from a PDF file and saves the extracted content into a plain text file.

# ALGORITM:
Step 1: Create a New Process Open UiPath Studio and create a new process named PDFTextExtractor.

Step 2: Install PDF Activities (If Needed) Go to Manage Packages → Official → Search for UiPath.PDF.Activities.

Install and save.
Step 3: Add Variables Create the following variables:

Name Type Default Value (if any) pdfPath String "C:\Users\YourName\Documents\Sample.pdf" textData String (leave blank) textPath String "C:\Users\YourName\Documents\Output.txt"
Step 4: Add Read PDF Text Activity Drag and drop the Read PDF Text activity from PDF Activities.

Set the properties:
FileName: pdfPath
Output: textData
Enable Preserve Formatting (optional)
Step 5: Write Text to File Drag and drop Write Text File activity.

Set the properties:
FileName: textPath
Text: textData
Encoding: UTF-8 (optional)
# PROGRAM:

<img width="1484" height="934" alt="image" src="https://github.com/user-attachments/assets/92c41f60-4d31-4386-9000-7cfb7c6d9424" />


# OUTPUT:

<img width="1427" height="733" alt="image" src="https://github.com/user-attachments/assets/5d5d5e23-6461-460b-b0d1-6e2b8d5c3e4a" />


# RESULT:
The UiPath workflow successfully reads the content from a PDF file and writes it into a .txt file using built-in PDF and File activities.
