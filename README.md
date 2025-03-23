# 🌐 Educational Website Copier & Form Modifier

![Python](https://img.shields.io/badge/Python-3.x-blue.svg) ![Selenium](https://img.shields.io/badge/Selenium-WebDriver-brightgreen.svg) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-HTML%20Parser-orange.svg) ![Requests](https://img.shields.io/badge/Requests-HTTP-yellowgreen.svg) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-UI-blueviolet.svg)

## 🚀 Project Overview

The **Educational Website Copier & Form Modifier** is a Python-based educational tool that helps you locally replicate websites. It uses modern automation tools like **Selenium** and **BeautifulSoup** to efficiently download dynamic content including HTML, CSS, JavaScript, and images. Additionally, it modifies login forms for educational demonstrations, capturing form submissions locally using a built-in PHP capture script and a user-friendly management panel powered by **TailwindCSS**.

Ideal for developers, students, and educators who want to learn about web scraping, automation, form interactions, and basic cybersecurity awareness.

---

## 🌟 Key Features

- ✅ **Automated Setup:** Installs necessary Python packages automatically.
- 🌎 **Comprehensive Website Download:** Captures dynamic sites using headless Selenium Chrome sessions.
- 🛠️ **Form Modification:** Quickly modifies login forms in HTML/PHP files to point to a local credential capture script.
- 📋 **Credential Capture:** Logs submitted form data to a structured JSON file.
- 🖥️ **Interactive Panel:** Easily manage and view captured data through an intuitive, TailwindCSS-powered interface.
- ⚙️ **Easy-to-Use Interface:** Clear prompts and colorful feedback using Colorama for enhanced CLI interaction.

---

## 📦 Requirements & Installation

### Step 1: Install Python Dependencies

Dependencies auto-install on first run. However, you can install them manually with:

```bash
pip install requests beautifulsoup4 colorama selenium webdriver-manager
```

### Step 2: Selenium & Chrome WebDriver

No manual ChromeDriver installation needed—handled automatically by the script.

---

## 🚦 Usage

Run the script:

```bash
python script.py
```

You'll interact through a simple menu to:

1. Download and export websites locally.
2. Modify login forms in existing HTML/PHP files.
3. Generate `capture.php` for educational credential capturing.
4. Generate `panel.php` to manage and view captured data.

---

## 📌 Detailed Workflow

- **Website Download:** Selenium navigates and downloads the fully rendered site, including JS, CSS, and images.
- **Form Modification:** Scans directories, detects login forms, and modifies them to post data to `capture.php`.
- **Credential Capture:** Captures submitted form data securely into JSON format for educational insights.
- **Management Panel:** View, edit, or delete captured data via a visually appealing web interface.

---

## 🚨 Educational Purposes Only

This tool is strictly for educational purposes. Use responsibly and ethically.

---

## 🙏 Acknowledgments

Special thanks to maintainers of:

- [Selenium](https://www.selenium.dev/)
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/)
- [Requests](https://requests.readthedocs.io/)
- [Colorama](https://github.com/tartley/colorama)
- [WebDriver Manager](https://github.com/SergeyPirogov/webdriver_manager)
- [TailwindCSS](https://tailwindcss.com/)

---

📌 **© 2025 Educational Website Copier & Form Modifier Project | Developed by Jason**

Enjoy learning! 🎓🚀✨

