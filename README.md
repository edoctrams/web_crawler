# Web Crawler (Colab Edition)

This mini project is a simple web crawler built using **Python**, **Requests**, and **BeautifulSoup** in **Google Colab**. It takes a website URL as input, extracts all hyperlinks from the page, and saves them to a `.txt` file.

---

##  Features

- Crawls a given web page
- Extracts all `<a href="">` hyperlinks
- Displays links in Colab output
- Saves links to a file (`found_links.txt`)

---

## ▶ How to Run

1. Open the notebook in Google Colab
2. Run the cell to install `beautifulsoup4`
3. Input a valid URL (e.g. https://example.com)
4. View and download `found_links.txt` from the left sidebar or use:

```python
from google.colab import files
files.download("found_links.txt")
