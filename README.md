# YTViews
Extracts the View count of youtube videos via an Google Sheet

## Requirements
- a Google account
- Python 3.10.7 or newer. Download [here](https://www.python.org/).

## Preparation
1. Install requirements
```sh
pip install -r requirements.txt
```
2. Follow instructions on the [Google Workspace Python quickstart guide](https://developers.google.com/docs/api/quickstart/python) to ensure API access. Download your **credentials.json** file and place it in the root folder of the project.
3. Head to [Google Docs Spreadsheets](https://docs.google.com/spreadsheets/) and create your own sheet or clone the [sample sheet](https://docs.google.com/spreadsheets/d/1ypg-aT4fVPMarFrU4SlvafBXVT6knGwxBBVcxDlJQ2U).
4. Extract the sheet ID from your Sheet URL. The sheet ID is the bold part of the following example: docs.google.com/spreadsheets/d/**1ypg-aT4fVPMarFrU4SlvafBXVT6knGwxBBVcxDlJQ2U**/edit#gid=0
5. Apply the ID to the [appropriate line](https://github.com/ThatH4tGuy/YTViews/blob/927d1d420be0cfbf03f51d6d3815c5824f986f3e/main.py#L14) in main.py

## Running the script
```sh
python main.py
```

## Relevant URLs:
* [Google Cloud Console](https://console.cloud.google.com/)
* [Sample Sheet](https://docs.google.com/spreadsheets/d/1ypg-aT4fVPMarFrU4SlvafBXVT6knGwxBBVcxDlJQ2U)
* [Google Workspace Python quickstart guide](https://developers.google.com/docs/api/quickstart/python)
