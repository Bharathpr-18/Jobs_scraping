# Fake Jobs Web Scraper

## Project Overview

This project is a Python-based web scraper that extracts job listings from the Fake Jobs website provided by Real Python.

The scraper collects:

- Job Title
- Company Name
- Location
- Job Detail URL

The extracted data is stored in a CSV file for further analysis.

---

## Website Used

https://realpython.github.io/fake-jobs/

---

## Features

- Scrapes job information from a website
- Extracts multiple fields from each job posting
- Handles missing data gracefully
- Stores results in CSV format
- Clean and beginner-friendly Python code

---

## Technologies Used

- Python 3
- Requests
- BeautifulSoup4
- CSV Module

---

## Project Structure

```
FakeJobsScraper/
│
├── scraper.py
├── jobs.csv
├── README.md
```

---

## Installation

### Clone the repository

```bash
git clone <repository-url>
cd FakeJobsScraper
```

### Install dependencies

```bash
pip install requests beautifulsoup4
```

---

## How to Run

Execute the following command:

```bash
python scraper.py
```

After successful execution, a file named `jobs.csv` will be created.

---

## Sample Output

| Job Title | Company Name | Location | Job URL |
|------------|-------------|------------|----------|
| Senior Python Developer | Payne, Roberts and Davis | Stewartbury, AA | URL |
| Energy Engineer | Vasquez-Davidson | Christopherville, AA | URL |
