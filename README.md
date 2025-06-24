# 🔍 GitHub Profile Finder

A sleek and dynamic web application that allows users to search for any GitHub username and view detailed profile information, including repositories, followers, and additional social links like LinkedIn and email (if provided).

## 🚀 Features

- 🔎 Search by GitHub username
- 🧑‍💻 Displays user profile information:
  - Avatar (clickable, redirects to GitHub profile)
  - Name, bio, location, company
  - Public repos, followers, following
  - Blog/website link
- 📂 Lists latest repositories (5 recent)
- 🌐 Shows additional contact details (LinkedIn & Email) for known users
- 🌙 Light/Dark mode toggle
- 🌌 Animated background for an elegant UI

## 📁 Project Structure

```
project-root/
├── index.html          # Main HTML file
├── style.css           # Custom styles
├── script.js           # JavaScript logic
└── README.md           # This file
```

## 🛠️ How to Use

1. Clone this repository or download the files.
2. Open `index.html` in any modern web browser.
3. Enter a valid GitHub username in the search bar and click **Search**.
4. The user’s profile and recent repositories will be displayed.

## 🧠 Customization

To add known LinkedIn or email links for certain GitHub users, update the `socialInfo` object in `script.js`:

```js
const socialInfo = {
  "octocat": {
    linkedin: "https://linkedin.com/in/example-octocat",
    email: "octocat@example.com"
  },
  "torvalds": {
    linkedin: "https://linkedin.com/in/linus-torvalds",
    email: "torvalds@linux.org"
  }
};
```

## 🧩 Dependencies

- [GitHub REST API](https://docs.github.com/en/rest/users/users)
- [Font Awesome](https://fontawesome.com/) for icons

## 📌 Note

- GitHub API rate-limits unauthenticated requests. You might need a token if making many queries in a short time.
- LinkedIn and Email data is **manually provided** for privacy reasons (not fetched from GitHub API).

## 📄 License

This project is open source and free to use for educational and personal use.

---

> Built with ❤️ by [ Deepanshu Raj, Deepraj Kushwaha , Bittu Kumar ]


🔗 𝗟𝗶𝘃𝗲 𝗦𝗶𝘁𝗲: https://lnkd.in/dimpPtAG

