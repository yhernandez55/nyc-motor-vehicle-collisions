# nyc-motor-vehicle-collisions

## Project Summary
This project analyzes motor vehicle collisions in New York City using data from NYC OpenData. The goal is to identify trends, contributing factors, and patterns in accidents that could help inform policy changes and improve road safety.

As part of this project, I created a **poster presentation** that highlights key findings from the analysis. You can view the poster here:

📌 [View Project Poster](TDSP_Poster.pdf)

This repository contains a Jupyter notebook for analyzing motor vehicle collisions in New York City. To run the notebook, follow the steps below:

## Prerequisites:
1. Download the dataset manually from [NYC OpenData](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).

2. Once downloaded, you have two options:
   - **Option 1:** Upload the dataset to your **Google Drive** (recommended for Google Collab users).
   - **Option 2:** Place the dataset in the same directory as the notebook if you're running it **locally** (e.g., in VSCode, JupyterLab, or another environment).

## Running the Notebook:
1. Open the notebook in [Google Collab](https://colab.research.google.com/).

2. **Downloading the Data:** Load the Data Directly from the URL 

   You can attempt to load the dataset directly using the following code:

   ```python
   csv_url = "https://data.cityofnewyork.us/resource/h9gi-nx95.csv"
   data = pd.read_csv(csv_url)
