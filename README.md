# BizCardX-Extracting-Business-Card-Data-with-OCR
BizCardX: Extracting Business Card Data with OCR

## Overview

BizCardX is a Streamlit web application for extracting business card information using OCR (Optical Character Recognition). This application allows users to upload an image of a business card and extract relevant information, such as company name, cardholder name, designation, contact details, and more. Users can also view, modify, or delete the extracted data within the app. Additionally, the app provides the functionality to save the extracted information into a MySQL database along with the uploaded business card image.

## Technologies Used

- Python
- Streamlit
- EasyOCR
- MySQL
- Pandas
- OpenCV
- PIL (Pillow)

## Features

- Extract business card data using Optical Character Recognition (OCR).
- Display the uploaded business card with highlighted text.
- View, modify, or delete the extracted data.
- Save the extracted information into a MySQL database.
- Beautiful background and user interface.

## Getting Started

### Prerequisites

Make sure you have the following libraries and tools installed:

- Python
- Streamlit
- EasyOCR
- MySQL Server
- Pandas
- OpenCV
- Pillow (PIL)

### Installation

##1.Install the required Python packages:
pip install pandas streamlit easyocr mysql-connector-python opencv-python pillow

##2.Set up your MySQL database and configure the connection details in the code.
Run the Streamlit application:

## Usage
Choose the "Upload & Extract" menu.
Upload an image of a business card.
The application will extract information from the card using OCR.
You can view the extracted data, modify it, or delete it.
Click "Upload to Database" to save the data into your MySQL database.

## Acknowledgments
Aravinth for creating this OCR application.
The developers of Streamlit, EasyOCR, and other open-source libraries used in this project.

### screenshots

## Upload an image file to extract data
![WhatsApp Image 2023-10-17 at 3 06 02 PM](https://github.com/aravinthbalaiyan/BizCardX-Extracting-Business-Card-Data-with-OCR/assets/144364538/85d5a507-6203-4707-b35c-0b657a75f8ca)

## All data in Database
![WhatsApp Image 2023-10-17 at 3 06 20 PM](https://github.com/aravinthbalaiyan/BizCardX-Extracting-Business-Card-Data-with-OCR/assets/144364538/e28ece48-beb6-4bf9-8f0a-3a4f0035d1ea)

## Modify data in database
![WhatsApp Image 2023-10-17 at 3 06 55 PM](https://github.com/aravinthbalaiyan/BizCardX-Extracting-Business-Card-Data-with-OCR/assets/144364538/f99a9479-58e7-4d2a-8b74-01e048a9cf5a)
