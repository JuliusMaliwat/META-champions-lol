# Project Title: Unveiling META Champions in League of Legends (Patch 13.24)

## Project Summary
This project aims to analyze the META (Most Effective Tactics Available) within the popular online multiplayer game, League of Legends (LoL), specifically focusing on patch 13.24. By utilizing web scraping and API data retrieval techniques, we gathered comprehensive information about champions, focusing on identifying those who are considered META within the current gaming environment. The project's objective was to provide players with a strategic advantage by highlighting the most powerful and influential characters in the latest game version, enhancing their chances of success.

### Key Insights:
- Identification of META champions and their roles in the current patch.
- Analysis based on data collected from Riot Games API, Lolalytics, Blitz.gg, and Op.gg.
- Emphasis on data quality, ensuring completeness and consistency across the dataset.

## Environment Setup
To get started with this project, follow the steps below:

### 1. Install Dependencies
Install the necessary Python packages by running:
```
pip install -r requirements.txt
```

### 2. Local MySQL Connection
Configure a local connection in MySQL Workbench with your preferred settings.

### 3. Update Connection Credentials
Update the database connection settings in the code with your MySQL Workbench credentials (host, user, password, database name) to enable interaction with your MySQL database.

### 4. Notebook Execution
Execute the notebooks in the following order:

1. **Data Acquisition**
   - `data_acquisition_api`
   - `data_acquisition_scraping_lolalytics`
   - `data_acquisition_scraping_opgg`
   - `data_acquisition_scraping_blitz`

2. **Data Integration**
   - `data_integration`

3. **Data Cleaning**
   - `data_cleaning`

4. **Data Quality**
   - `data_quality`

5. **Data Storage**
   - Prior to execution, ensure you have entered your MySQL credentials in the code as mentioned above.
   - `data_storage`

6. **Query**
   - Similarly, verify that your MySQL credentials are correctly inserted before running this notebook.
   - `query`

Ensure each notebook is fully executed before moving to the next.


Make sure each notebook is fully executed before moving to the next one.
