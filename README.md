# nyc-motor-vehicle-collisions

This repository contains a Jupyter notebook for analyzing motor vehicle collisions in New York City. To run the notebook, follow the steps below:

## Prerequisites:
1. Download the dataset by clicking on the following link:  
   [Download Motor Vehicle Collisions Dataset](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)

2. Once downloaded, you have two options:  
   - **Option 1:** Upload the dataset to your **Google Drive** (recommended for Google Colab users).  
   - **Option 2:** Place the dataset in the same directory as the notebook if you're running it **locally** (e.g., in VSCode, JupyterLab, or another environment).

## Running the Notebook:
1. Open the notebook in [Google Colab](https://colab.research.google.com/).

2. If you uploaded the dataset to Google Drive, **use this code** to mount your drive and read the file:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')

   # Read the data using pandas read_csv function from Google Drive
   data = pd.read_csv("/content/drive/MyDrive/Motor_Vehicle_Collisions_-_Crashes_20250112.csv")
