# FBI Cyber's Most Wanted Scraper

This project automates the collection of publicly listed cybercrime suspects from the [FBI Cyber's Most Wanted](https://www.fbi.gov/wanted/cyber) webpage. It extracts detailed profile information from each individual listing and compiles the data into a structured CSV file.

---

## 🚀 Features

- 🔗 Scrapes individual suspect profile pages
- 🧠 Extracts key details such as:
  - Name
  - Aliases
  - Date(s) of Birth
  - Place of Birth
  - Nationality, Race, Sex, etc.
- 💾 Saves to CSV (`cyberwanted_profile.csv`) immediately after each entry
- 🗂 Avoids duplication and supports resume on rerun
- 🌐 CAPTCHA handling
- 🕓 simulate human browsing

---

## 🧰 Tech Stack

- Python 3.9+
- [Playwright (Async)](https://playwright.dev/python/)
- [BeautifulSoup (bs4)](https://pypi.org/project/beautifulsoup4/)
- Pandas

---
