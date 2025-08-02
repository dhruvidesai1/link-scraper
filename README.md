# 🔗 Web-Based Link Scraper

A Django-based web application that allows users to submit websites, automatically scrape hyperlinks, and manage scraped links via a simple web interface and admin panel.
[![Python](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/downloads/release/python-3120/)
[![Django](https://img.shields.io/badge/django-5.2-green.svg)](https://www.djangoproject.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
---

## 🚀 Features

- 🌐 Submit a URL and scrape all valid hyperlinks (`<a>` tags)
- 🗂️ Store and display scraped links
- ✅ Admin interface for reviewing and managing entries
- 🛡️ URL validation and error handling
- 💾 Persistent storage using SQLite (or any DB backend)

---

## 🛠️ Tech Stack

- **Backend:** Django 5.x
- **Frontend:** Bootstrap 4
- **Scraping:** BeautifulSoup (or requests + html.parser)
- **Database:** SQLite (default), PostgreSQL/MySQL compatible
