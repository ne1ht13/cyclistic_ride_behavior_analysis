# Cyclistic Bike-Share Analysis

This repository contains my analysis of Cyclistic (Divvy) bike-share trip data for the Google Data Analytics Capstone project.

Because the raw data is larger than 1 GB, **the data files are not stored in this GitHub repo**.  
Instead, this README explains how to download and set up the data locally so you can reproduce the analysis.

---

## Project Structure

```text
.
├── bikeshare_analysis.Rmd   # Main R Markdown analysis file
├── data/                    # Folder where raw CSV files should be placed (NOT tracked by git)
└── .gitignore

## 2. Download & Place the Data Files

1. **Go to the official data page**

   Open the Divvy/Cyclistic trip data page in your browser:

   - https://divvy-tripdata.s3.amazonaws.com/index.html

2. **Download the 12 monthly data files**

   Download the ZIP files for **July 2023 – June 2024**:

   - `202307-divvy-tripdata.zip`
   - `202308-divvy-tripdata.zip`
   - `202309-divvy-tripdata.zip`
   - `202310-divvy-tripdata.zip`
   - `202311-divvy-tripdata.zip`
   - `202312-divvy-tripdata.zip`
   - `202401-divvy-tripdata.zip`
   - `202402-divvy-tripdata.zip`
   - `202403-divvy-tripdata.zip`
   - `202404-divvy-tripdata.zip`
   - `202405-divvy-tripdata.zip`
   - `202406-divvy-tripdata.zip`

3. **Unzip the files**

   Extract each ZIP file. You should get 12 CSV files:

   - `202307-divvy-tripdata.csv`
   - `202308-divvy-tripdata.csv`
   - `202309-divvy-tripdata.csv`
   - `202310-divvy-tripdata.csv`
   - `202311-divvy-tripdata.csv`
   - `202312-divvy-tripdata.csv`
   - `202401-divvy-tripdata.csv`
   - `202402-divvy-tripdata.csv`
   - `202403-divvy-tripdata.csv`
   - `202404-divvy-tripdata.csv`
   - `202405-divvy-tripdata.csv`
   - `202406-divvy-tripdata.csv`

4. **Create the `data` folder**

   In the root of this project (the same folder as `bikeshare_analysis.Rmd`), create a folder named:

   - `data`

5. **Move all CSV files into the `data` folder**

   Move the 12 CSV files into the `data` folder so the structure looks like:

   ```text
   .
   ├── bikeshare_analysis.Rmd
   ├── data
   │   ├── 202307-divvy-tripdata.csv
   │   ├── 202308-divvy-tripdata.csv
   │   ├── 202309-divvy-tripdata.csv
   │   ├── 202310-divvy-tripdata.csv
   │   ├── 202311-divvy-tripdata.csv
   │   ├── 202312-divvy-tripdata.csv
   │   ├── 202401-divvy-tripdata.csv
   │   ├── 202402-divvy-tripdata.csv
   │   ├── 202403-divvy-tripdata.csv
   │   ├── 202404-divvy-tripdata.csv
   │   ├── 202405-divvy-tripdata.csv
   │   └── 202406-divvy-tripdata.csv
   └── .gitignore