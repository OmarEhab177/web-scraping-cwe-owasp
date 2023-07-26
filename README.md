Sure, here's the updated README.md file to reflect the changes you mentioned:

---

# Web Scraping CWE and OWASP Headers

This Python script allows you to perform web scraping to extract headers from the Common Weakness Enumeration (CWE) and Open Web Application Security Project (OWASP) websites. It utilizes the Selenium library to navigate through web pages and BeautifulSoup to parse the HTML content and extract the relevant headers.

## Prerequisites

- Python 3.x
- Google Chrome web browser (since the script uses Chrome as the browser)
- ChromeDriver (ensure that the version of ChromeDriver matches your Chrome browser version)

## Installation and Usage

1. Clone the repository from GitHub:

```bash
git clone https://github.com/OmarEhab177/web-scraping-cwe-owasp.git
```

2. Navigate to the project directory:

```bash
cd web-scraping-cwe-owasp
```

3. Install the required Python libraries using pip:

```bash
pip3 install -r requirements.txt
```

4. Run the script using the following command:

```bash
python3 scripts.py
```

5. The script will prompt you to enter a search term for CWE and OWASP. If you leave the OWASP search term blank, it will take the CWE search term as the default.

6. You will also be asked if you want to view the links after scraping the data. Enter 'y' if you want to view the links or 'n' if you only want to see the titles.

7. The script will launch the Chrome web browser, perform the web scraping, and display the CWE and OWASP headers.

8. The headers will be printed in the terminal or command prompt, and you can choose to view the links associated with each header based on your input in step 6.

9. After completing the web scraping, the Chrome browser will be closed automatically.

**Important Note:** Web scraping may be subject to the website's terms of service. Please use this script responsibly and ensure that you have the right to access and scrape data from the CWE and OWASP websites.
