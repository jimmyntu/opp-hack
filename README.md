# Scaffolding for Google Colabs script for conversation data analysis

This is scaffolding script for Google Colabs Notebook script. Follow the following guide.

## Setup Guide
1. Login to [Google Colabs](https://colab.research.google.com/)
2. Choose "Upload"
3. Upload file **parser_func.ipynb** 
4. Upload file **main.ipynb** 

make sure both notebook scripts are in the same folder in your Google Drive. If you have specific folder in Google Drive, make sure to modify the path in *main.ipynb*

```
libdir = "/content/gdrive/My\ Drive/Colab\ Notebooks/"
```

## Usage Guide

Run each cell in **main.ipynb**

1. First cell is to load all functions for file parser and process the data. If there is pop-up in "Permit this notebook to access your Google Drive files". Click "Connect to Google Drive". Make sure to use the same Google account as you upload the notebook script. When you see green tick, the module is loaded. 
2. Second cell is to upload sample.json file, and prepare data. Click "Choose Files", and upload sample.json file. 
3. Third cell is to generate report for selected user and date range. Choose user, start and end date; click "Generate Report" button. It will proceed to analyze and generate report. 
