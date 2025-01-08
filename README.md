# Exploratory-NBA-Analysis
- Python version 3.12.5 used

List of major dependencies:
- from nba_api.stats.endpoints import leaguedashteamstats (for documentation see: https://github.com/swar/nba_api/blob/master/README.md)
- import pandas as pd
- import requests
- from bs4 import BeautifulSoup
- import matplotlib.pyplot as plt
- import seaborn as sns

**Ideal execution of code**:

**Option 1:**
- Download **NBA_Final_Project.ipynb** locally and execute the code, this code will load in the api data and webscrape the data as well. I prefer jupyter notebooks as I find them easier to interact with and I've left comments embedded explaining my code logic.
If you have Visual Studio Code installed:

1) Open the repository folder in Visual Studio Code.
2) Install the "Jupyter" extension from the Extensions Marketplace.
3) Open the NBA_Final_Project.ipynb file, and VS Code will automatically open it in the notebook interface.
4) Run the cells using the Play button in the interface.

**Option 2:**
1) Install Jupyter Notebook in your terminal
2) Clone this GitHub repository to your local machine using git clone
3) In the Jupyter Notebook interface, navigate to the NBA_Final_Project.ipynb file and click on it to open
4) Run the cells of code

**Option 3:**
1) If running into any api data related errors, just grab the raw data from the folder and load it in
2) If still running into errors, source code can be grabbed from the src/ directory under analyze_data.py, clean_data.py, get_data.py, visualize_results.py. All of this source code is already in the NBA_Final_Project.ipynb, but it is also located here if needed. 


