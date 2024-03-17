# BizCardX_Extracting-_Business_Card_Data_with_OCR
Data Extraction from Business Cards using easyOCR | Streamlit GUI | SQL Database

**INTRODUCTION:**
The objective of this project is to develop a Streamlit application that enables users to upload a business card image and extract essential information from it using easyOCR. The extracted information includes the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted details will be displayed in a user-friendly graphical user interface (GUI).

**TECHNOLOGIES & TOOLS USED:**
-Python
-Streamlit
-easyOCR
-Postgres

**ETL and EDA PROCESS:**
**a) Extracting the data**
Extract the particular business card data by using easyocr.
**b) Transforming the data**
After the extraction process, the text data extracted is converted into a structured data in the form of dataframe.
**c) Loading data**
After the transformation process, the data in the form of dataframe is stored in the postgreSQL database.
**d) Visualizing, Updating, deleting the data**
The extracted data can be visualized using matlplotlib and in the form of dataframe.The data can also be updated, modified and deleted from the database.

**USER GUIDE**
**Step 1. Home Tab**
-It provides a brief overview of the project and the tools required for the project.
**Step 2. Upload Tab**
-In this tab, Browse a business card file (image) using browse file button and upload the image in upload here section. The image will be processed, required data will be collected. The processed image will appear with collected data in the text format. Upoad the data to PostgreSQL by clicking upload to the database button.The fetched data will appear in the form of data frame(i.e., table).
**Step 3. Modify Tab**
-In this page, we can change/alter the data collected from a business card, uplaod the modified data to the postgreSQL database and then we can view the modified data as well.
**Step 4. Delete Tab**
-In this page, we can delete the data collected from a business card in database and view the existing data from postgreSQL.

**RESULT:**
-The result of this project would be a Streamlit application that allows users to upload an image of a business card and extract relevant information from it using easyOCR.The extracted information would include the company name, card holder name,
designation, phone_number, email, website, area, city, state, pincode and binary data of image.The extracted information would then be displayed in the application's graphical user interface (GUI).The application would also allow users to save the extracted information into a database along with the uploaded business card image. The database would be able to store multiple entries, each with its own business card image and extracted information.

-The final application would have a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. The extracted information would be displayed in a clean and organized manner, and users would be able to easily add it to the database with the click of a button.

