# browser-extension-lookup

## Lookup web browser extensions by their Identifier


Some dependancies are required in Ubunutu 24.04 LTS. Previous versions of Ubuntu may vary with how-to especially with lxml_html_clean.

This repo shows how to achieve this via python.

Note: For Windows you can maybe use the ChromeDriver with PowerShell and/or leverage Selenium to achieve a similar result to scrape the data.


```
python3 -m venv .venv
source .venv/bin/activate
pip install requests
pip install requests_html
pip install bs4
pip install lxml_html_clean
```

## Usage

Edge

`python3 edge-extensions.py edge.txt`

Chrome

`python3 chrome-extension-search.py chrome-exts.csv`
