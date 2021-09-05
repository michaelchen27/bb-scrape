
## Barangbaku Product Scraper
 Get all product information and save to an Excel Spreadsheet

### Setup Guide
1. Download chrome driver <a href="https://chromedriver.chromium.org/downloads">here</a>
2. Edit the Chrome Driver path (hint: variable named chromeDriverPath)
3. Edit the Spreadsheet path (hint: variable named wbPath)
4. Run all cell with Jupyter Notebook.
5. All done.

### Convert ipynb to exe:
`.ipynb` -> `.py`:
````python
pip install nbconvert
jupyter nbconvert --to script my_notebook.ipynb
````
This will generate a `.py` file. From this `.py` file, generate the `.exe`
<br>

`.py` -> `.exe`:
````python
pip install pyinstaller
pyinstaller my_notebook.py
````

The executable file should be inside the `dist` directory.
