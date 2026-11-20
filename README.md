# Northwind SQL & Pandas Lab 

> Querying employee records and order revenue from SQLite straight into Pandas DataFrames. 

--- 

### What's Inside 
| File | Purpose | 
| :--- | :--- | 
| `main.py` | 9 SQL-to-Pandas queries covering filtering, `CASE` logic, string slicing, rounding, and date formatting | 
| `data.sqlite` | Fictional Northwind company database (`employees`, `orders`, `orderDetails`) | 
| `test_main.py` | Automated `pytest` suite verifying every query output | 

--- 

### Query Highlights 
* **Employee Directory:** Column selection, ordering, and custom aliasing (`ID`) 
* **Role Classification:** Conditional `CASE` binning (`Executive`vs. `Not Executive`) 
* **String Shaping:** Measuring `lastName` lengths and extracting 2-letter `jobTitle` prefixes 
* **Order Analytics:** Calculating rounded line-item totals (`$9,604,251`) and splitting dates into `day`, `month`, and `year`

--- 
###  Run & Verify 
```bash 
pipenv install 
pipenv run pytest ``` 

*Built with Python, SQLite3, and Pandas.*