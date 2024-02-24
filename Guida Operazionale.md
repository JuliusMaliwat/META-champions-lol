# Operational Guide

## Environment Setup

### 1. Install Dependencies
- Run the following command in your project directory to install the necessary Python packages:
  ```
  pip install -r requirements.txt
  ```

### 2. Local MySQL Connection
- Configure a local connection in MySQL Workbench with your preferred settings.

### 3. Update Connection Credentials
- Before executing the `data_storage` and `query` notebooks, locate the section in the code designated for database connection settings.
- Input your MySQL Workbench local connection credentials (host, user, password, and database name) to enable the notebooks to interact with your MySQL database.

### 4. Notebook Execution

Run the following notebooks in order:

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
