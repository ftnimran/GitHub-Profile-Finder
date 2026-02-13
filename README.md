# 🔍 GitHub Profile Finder

GitHub Profile Finder ek simple aur powerful web app hai jisme user **GitHub username** enter karta hai aur turant uski **GitHub profile details** dekh sakta hai. Ye project GitHub API ka use karke real-time data fetch karta hai.

🌐 **Live Demo:** https://github-profile-finder-505.netlify.app  

---

## 🚀 Features

- 🔎 GitHub username search
- 👤 User profile details (name, username, bio)
- 🖼️ Profile image (avatar)
- 📦 Public repositories count
- 👥 Followers & Following
- 🔗 Direct GitHub profile link
- ⚠️ User not found error handling
- ⏳ Loading state (optional enhancement)

---

## 🛠️ Tech Stack

- **HTML** – Structure
- **CSS / Tailwind CSS** – Styling
- **JavaScript (ES6+)** – Logic
- **GitHub REST API** – Data source

---

## 🌐 GitHub API Used

```
https://api.github.com/users/{username}
```

Example:

```
https://api.github.com/users/octocat
```

---

## 📁 Project Structure

```
GitHub-Profile-Finder/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## ⚙️ How It Works

1. User input field me GitHub username dalta hai
2. Button click par GitHub API call hoti hai
3. API se data aata hai (JSON format)
4. Data UI me display hota hai
5. Agar username galat ho → error message show hota hai

---

## 📌 Learning Outcomes

- API fetching using `fetch()`
- Async / Await ka use
- DOM manipulation
- Error handling
- Real-world frontend project experience

---

## 🌱 Future Improvements

- 📊 Repositories list show karna
- ⭐ Most starred repo highlight
- 📱 Fully responsive UI

---

## 🧑‍💻 Author

**Imran Ali**  
Frontend Developer | Learning Full Stack 🚀

---

⭐ Agar ye project pasand aaye to repo ko **star** karna mat bhoolna!
