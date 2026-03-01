# 📘 Selenium Facebook Friend List Scraper

A command-line automation tool built using **Python, Selenium, and BeautifulSoup** to automate Facebook login and extract a user's friend list.

This project demonstrates practical browser automation, dynamic content handling, and structured data extraction from modern web applications.

---

## 🚀 Features

- Automated Facebook login
- Headless Firefox support
- Dynamic scrolling for lazy-loaded friend lists
- Extraction of:
  - Friend names
  - Facebook profile IDs
- Data export formats:
  - ✅ JSON (default)
  - ✅ CSV
  - ✅ Raw HTML source
- Offline parsing from saved HTML
- Command-line configurable options

---

## 🛠 Tech Stack

- Python 3
- Selenium WebDriver
- Mozilla Firefox + GeckoDriver
- BeautifulSoup4
- Regular Expressions
- argparse (CLI configuration)
- JSON / CSV serialization

---

## 📦 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2️⃣ Install Dependencies

```bash
pip install selenium beautifulsoup4
```

### 3️⃣ Install Requirements

Ensure:
- Firefox browser is installed
- GeckoDriver is available in your system PATH

---

## ▶ Usage

### Basic Execution

```bash
python scraper.py
```

You will be prompted to enter:
- Email or phone number
- Password

---

### Headless Mode (Background Execution)

```bash
python scraper.py --headless
```

---

### Export as CSV

```bash
python scraper.py --csv
```

---

### Import from Saved HTML (Offline Mode)

```bash
python scraper.py --import-html savedfile.html
```

---

## ⚙ Command Line Options

| Option | Description |
|--------|------------|
| `-v`, `--verbose` | Enable verbose logging |
| `-b`, `--headless` | Run Firefox in headless mode |
| `-t`, `--timeout` | Set element wait timeout (default: 30s) |
| `-j`, `--json` | Export JSON (default) |
| `-c`, `--csv` | Export CSV |
| `-s`, `--html` | Export raw HTML source |
| `-i`, `--import-html` | Parse previously saved HTML |
| `-l`, `--login-data` | Read login credentials from file |

---

## 🧠 What This Project Demonstrates

This repository highlights:

- Automation of dynamic web applications
- Explicit waits and synchronization handling
- Infinite scroll automation
- DOM parsing with BeautifulSoup
- Regex-based data extraction
- CLI tool architecture
- Structured data serialization
- Error handling and user prompts

---

## ⚠ Ethical & Legal Notice

This project was developed strictly for:

- Educational purposes  
- Automation learning  
- Research experimentation  

Users are responsible for complying with Facebook’s Terms of Service and applicable laws. Automated scraping of platforms may violate service agreements.

This tool is not intended for commercial or abusive use.

---

## 🔮 Possible Improvements

- Refactor deprecated Selenium methods to Selenium 4 standards
- Add structured logging
- Add Docker support
- Add automated unit tests
- Improve resilience against UI structure changes
- Implement graph-based analysis of extracted connections

---

## 👤 Author

**Fahad Amin**  
SQA Automation Engineer  
Interested in intelligent automation systems, data-driven testing, and AI-enhanced reliability engineering.
