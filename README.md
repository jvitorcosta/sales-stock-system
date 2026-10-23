# Sales & stock system (prototype)

An early Streamlit prototype for my family's store: product stock control backed by a Google Sheets spreadsheet, with pages to look up, add, update and remove products.

**Status:** early prototype. The page layout and the Google Sheets connection exist; the insert, update and delete functions are still stubs. The store's real system is being rebuilt as a separate project.

## Run it

```sh
pip install -r requirements.txt
streamlit run sales-stock-system/app.py
```

It needs Google service-account credentials in Streamlit secrets to reach the spreadsheet.

**Stack:** Python, Streamlit, Google Sheets
