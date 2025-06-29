# 🕵️‍♂️ SabbonaScan – Professional Website Scanner

`SabbonaScan` is a powerful, professional-grade website scanner developed by **Sabbona Tessema**. It performs deep website crawling and downloads static assets like HTML, CSS, JS, images, and fonts into an organized file structure.

---

## 🚀 Features

- 🌐 **Target Any Website:** Provide any URL as the scan target.
- 🔍 **Deep Scanning:** Crawl pages up to configurable depth and max page limit.
- 📥 **Asset Downloader:** Automatically fetches HTML, CSS, JS, images, and fonts.
- 🗂️ **Clean File Structure:** Output stored in well-organized folders.
- 📊 **Scan Summary Report:** Displays number of files, total size, and categories.
- 📁 **JSON Output Tree:** Saves a file tree as `sabbona_file_tree.json`.

---

## 🧪 Example Usage

```bash
$ python sabbona_scan.py --url https://example.com --depth 5 --max-pages 500
