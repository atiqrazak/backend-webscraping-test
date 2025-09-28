# Reddit Web Scraper (Selenium)

This repository contains a simple web scraper built with **Python** and **Selenium** to extract posts from Reddit.  
The scraper fetches post titles, links, and other metadata, and saves the results into JSON/HTML files.

---

## 📌 Features
- Scrapes Reddit posts from a given subreddit.
- Saves results in:
  - `reddit_posts.json` → structured post data  
  - `rmalaysia_post_image.html` → simple HTML display of scraped posts
- Uses **Selenium WebDriver** for dynamic content scraping.

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/reddit-web-scraper.git
cd reddit-web-scraper
```

### 2. Install WebDriver
[Install WebDriver](https://sites.google.com/chromium.org/driver/)

### 3. (Optional) Install Live Preview in VS Code

To preview the scraped HTML output (rmalaysia_post_image.html) directly in VS Code:
1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for Live Preview (by Microsoft)
4. Click Install

## 🚀 Usage

### 1. Open Jupyter Notebook and run:
```bash
jupyter notebook web_scraper_selenium.ipynb
```

### 2. Open HTML file or Right-click HTML file in VSCode → Open with Live Preview
`rmalaysia_post_image.html`
