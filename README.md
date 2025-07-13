# 🎬 Movie Watchlist CLI App

A simple command-line interface (CLI) application for managing your movie watchlist using Python and SQLite.

---

## 📁 Project Structure
```bash
Movie-Watchlist/
├── app.py           # Entry point of the application
├── database.py      # Database logic and queries
├── requirements.txt # Python dependencies (optional for this app)
└── README.md        # Project documentation
```

---

## 🧰 Prerequisites

- Python **3.8+**
- Terminal or command-line access

> ⚠️ `sqlite3` is used for storage and comes with Python's standard library—no installation needed.

---

## 🚀 Setup Instructions

Open a terminal and run the following commands:

```bash
# Step 1: Create a virtual environment
python3 -m venv .venv

# Step 2: Activate the virtual environment
source .venv/bin/activate          # On macOS/Linux
# .\.venv\Scripts\activate         # On Windows (PowerShell)

# Step 3: Install dependencies (optional in this app)
pip install -r requirements.txt

# Step 4: Run the app
python app.py
```

-----

## 🧹 Cleanup

To remove the virtual environment (optional):

```bash
deactivate
rm -r .venv   # On Unix/macOS
# rmdir /S .venv  # On Windows (CMD)
```

---

## ✨ Features

1. **Add movies** to your watchlist (with release date)
2. **View upcoming movies** (movies releasing after today)
3. **View all movies** in the database
4. **Mark movies as watched** (per user, with optional review and rating)
5. **View watched movies** (per user, with reviews/ratings)
6. **Add users** to the app
7. **Search movies** by partial title (case-insensitive)
8. **Plan to watch a movie** (per user, with optional expectation)
9. **View planned movies** (per user, with expectations)
10. **See all reviews for a movie**
11. **Exit** the app

---

## 📝 Usage

- When prompted, select an option by entering the corresponding number.
- Add users before marking or planning movies as watched.
- Dates must be entered in `dd-mm-YYYY` format.
- Movie IDs are shown in the movie lists and are required for marking, planning, or reviewing.
- You can add a review and rating (out of 100) when marking a movie as watched.
- You can add an "expectation" when planning to watch a movie.
- View all reviews and ratings for a movie by selecting the appropriate menu option.

---

## Notes

- No internet connection required—everything is local.
- Data is stored in `data.db` in the project directory.
- Tested on Python 3.12.7 (Fedora Linux).

----

## License

This project is for educational and personal use. Feel free to modify or extend it.