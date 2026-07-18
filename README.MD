# 🇧🇩 E2B: Advanced Bengali Phonetic Editor

An advanced, browser-based text editor that allows users to type in Bengali phonetically using English characters (e.g., typing "ami" outputs "আমি"). It uses the **Google Input Tools API** for highly accurate transliteration and features an intuitive UI with auto-save and word suggestion capabilities.

🔗 **Live Demo:** [https://e2b.theme-x.org](https://e2b.theme-x.org)  
🌐 **Brought to you by:** [theme-x.org](https://theme-x.org)

## ✨ Features

- **Real-Time Transliteration**: Type English words and press `Space` or `Enter` to instantly convert them into Bengali.
- **Smart Dropdown Suggestions**: Click on any converted Bengali word to view alternative Bengali spellings or revert to the original English word.
- **Auto-Save (Local Storage)**: Never lose your work! The editor automatically saves your text locally. Your content remains intact even if you accidentally close or reload the tab.
- **One-Click Clear**: A convenient button to wipe the editor and local storage when you're ready to start fresh.
- **No Installation Required**: Runs entirely in your web browser. Just open the HTML file and start typing.

## 🚀 How to Use

1. **Visit the Live Demo**: Go to [https://e2b.theme-x.org](https://e2b.theme-x.org) to use it directly.
2. **Run Locally**: Clone or download this repository, and open the `index.html` file in any modern web browser.
3. Start typing in English (e.g., "bangla") and press `Space` to see it convert to "বাংলা".
4. **Click** on any Bengali word to see a dropdown menu of alternative suggestions and the original English word.

*Note: An active internet connection is required for the transliteration to work, as it fetches data from the Google API.*

## 🛠️ Technical Details

- **HTML5 & CSS3**: For a clean, modern, and responsive user interface.
- **JavaScript (Vanilla)**: Handles the core logic, API fetching, DOM manipulation, and `localStorage` management.
- **ContentEditable `<div>`**: Used instead of a standard `<textarea>` to allow individual word targeting, background data storage, and interactive dropdowns.
- **Google Input Tools API**: Used to fetch the transliteration data efficiently.

## 📂 Project Structure

```text
.
├── index.html       # The main file containing HTML, CSS, and JavaScript logic.
└── README.md        # Documentation for the repository.
