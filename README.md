# Project: Web Scrapping

Overview

This workspace contains a Jupyter Notebook that demonstrates a simple web scraping workflow and saves results to a CSV file.

- Notebook: `Notebooks/web_scrapping.ipynb`
- Data: `Data/Project web scrapping.csv`


What the notebook does

- Loads libraries for HTTP requests and HTML parsing.
- Scrapes web pages (example code and selectors inside the notebook).
- Cleans and stores result rows into the CSV file in the `Data/` folder.

Requirements

Recommended Python packages (suggested):

- `pandas`
- `requests`
- `beautifulsoup4`
- `lxml` (optional, for faster parsing)
- `notebook` or `jupyterlab`

Quick setup (Windows PowerShell)

```powershell
# create a virtual environment
python -m venv .venv
# activate it in PowerShell
.\.venv\Scripts\Activate.ps1
# install packages
pip install pandas requests beautifulsoup4 lxml notebook
# start the notebook server (then open the notebook file)
jupyter notebook
```

How to run the notebook

1. Open PowerShell in the project root `c:\Users\USER\Documents\Project web scrapping`.
2. Activate your virtual environment (if used).
3. Start Jupyter: `jupyter notebook` and open `Notebooks/web_srapping.ipynb`.
4. Run cells sequentially. The notebook writes output to `Data/Project web scrapping.csv`.

Tips & notes

- If the notebook uses site-specific selectors or authentication, update the code cells accordingly before running.
- Respect website `robots.txt` and terms of service when scraping.
- If you want reproducible installs, create a `requirements.txt` with pinned versions: `pip freeze > requirements.txt`.

Contact

If you want changes to this README or help running the notebook, reply here and I can update it.
