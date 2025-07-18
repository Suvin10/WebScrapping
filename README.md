# WebScrapping
📚 Quote Guessing Game — Web Scraping Project in Python
This is a fun and interactive terminal-based Python game that challenges users to guess the author of a famous quote. The quotes are dynamically scraped from http://quotes.toscrape.com using BeautifulSoup and requests. The game includes a hint system that helps the player as they run out of guesses.

# 🎯 Quote Guessing Game — Web Scraping in Python 🕵️‍♂️

This is a fun and interactive **Python terminal game** where you guess the author of a randomly selected quote. All quotes are scraped live from [http://quotes.toscrape.com](http://quotes.toscrape.com) using **web scraping** techniques with `requests` and `BeautifulSoup`.

> ✅ Great for beginners learning web scraping, loops, conditionals, and terminal I/O.

---

## 📌 Features

- 🔄 Live quote scraping from the website
- 🎲 Randomly selected quotes each time you play
- 🧠 4 chances to guess the author
- 💡 Hints provided after each wrong guess:
  - Hint 1: Author’s birth date & location
  - Hint 2: First name initial
  - Hint 3: Last name initial
- ⏱️ `sleep()` delays mimic real-time scraping
- 📚 Fully implemented in a Jupyter Notebook

---

## 🧱 Technologies Used

- Python 3.x
- `requests`
- `BeautifulSoup4`
- `csv` (optional if extending for data saving)
- `random`
- `time`

---

## 📂 File Structure

```bash
📁 Quote-Guessing-Game/
│
├── 📄 Quote_Guessing_Game_using_Web_Scraping_in_Python.ipynb  # Main notebook
├── 📄 README.md  # Project documentation
