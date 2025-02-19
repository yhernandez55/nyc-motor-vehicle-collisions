# nyc-motor-vehicle-collisions

## Project Summary
This project analyzes motor vehicle collisions in New York City using data from NYC OpenData. The goal is to identify trends, contributing factors, and patterns in accidents that could help inform policy changes and improve road safety.

As part of this project, I created a **poster presentation** that highlights key findings from the analysis. You can view the poster here:

📌 [View Project Poster](TDSP_Poster.pdf)  

This repository contains a Jupyter notebook for analyzing motor vehicle collisions in New York City. To run the notebook, follow the steps below:

## Prerequisites:
1. Download the dataset manually as shown below under the section of running the notebook.

2. Once downloaded, you have two options:  
   - **Option 1:** Upload the dataset to your **Google Drive** (recommended for Google Colab users).  
   - **Option 2:** Place the dataset in the same directory as the notebook if you're running it **locally** (e.g., in VSCode, JupyterLab, or another environment).

## Running the Notebook:
1. Open the notebook in [Google Colab](https://colab.research.google.com/).

2. If you uploaded the dataset to Google Drive, **use this code** to mount your drive and read the file:

   ```python
   csv_url = "https://data.cityofnewyork.us/resource/h9gi-nx95.csv"
   data = pd.read_csv(csv_url)
   from google.colab import drive
   drive.mount('/content/drive')

   # Read the data using pandas read_csv function from Google Drive
   data = pd.read_csv("/content/drive/MyDrive/Motor_Vehicle_Collisions_-_Crashes_20250112.csv")
