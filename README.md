# 🎵 Music Recommendation Web App

A full-stack music rating and recommendation system built with Flask and SQLite. Users can register, log in, search songs, rate them, and receive community-based song recommendations.

---

## 🔑 Features

- User registration and login with session handling
- Secure password hashing with Werkzeug
- Song search functionality
- Users can rate songs
- Songs are ranked by average community ratings
- Personalized view of songs with your own ratings
- Admin auto-uploads song data from `songs.csv`

---

## ⚙️ Technologies Used

- Python
- Flask
- SQLite
- HTML/CSS (Jinja templates)
- pandas (for song data import)
- Werkzeug (for password hashing)

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/your-username/music-recommendation-app.git
cd music-recommendation-app
```

2. **Install dependencies**

```bash
pip install flask pandas werkzeug flask-session
```

3. **Place your `songs.csv`** in the root directory.

4. **Run the app**

```bash
python app.py
```

Open your browser and go to:  
👉 `http://localhost:5000`

---

## 🧪 Functionality Walkthrough

- `/register` – Create a new user account
- `/login` – Login to your account
- `/search` – Search for songs by title
- `/rate` – View list of songs and rate them
- `/recommend` – See songs ranked by average rating
- `/logout` – Log out securely

---

## 📝 Sample `songs.csv` Format

```csv
id,title,link
1,Song A,https://example.com/songA
2,Song B,https://example.com/songB
...
```

---

## 📌 Notes

- All sessions are stored on the server's filesystem.
- Genuinely missing ratings are marked as `"NA"`.
- Includes average ratings visible on song recommendations.

---

## 🙌 Credits

Developed by [Your Name]  
For academic or personal use.

---

## 📄 License

This project is licensed under the MIT License.
