# price-monitoring-tool

Python tool for checking auto parts prices by article and brand from shop.avtogut.ru.

## Features

- reads articles and brands from an Excel file
- logs into shop.avtogut.ru
- searches minimum prices by brand-specific page IDs
- prints results to terminal
- saves results to an Excel file

## Requirements

- Python 3.10+
- requests
- pandas
- python-dotenv
- openpyxl

Install dependencies:

```bash
pip install -r requirements.txt
