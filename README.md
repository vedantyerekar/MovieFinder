# 🎬 Mo-View

Mo-View is a full-stack movie web application built using HTML, CSS, JavaScript, Node.js, Express.js, and MongoDB Atlas. Users can browse popular movies, search for movies, and add, edit, or delete reviews. Movie information is fetched from the TMDB API, while reviews are managed through a custom REST API and stored in MongoDB.

---

## Features

- Browse popular movies
- Search movies by title
- Add, edit, and delete reviews
- Store reviews in MongoDB Atlas
- REST API built using Express.js

---

## Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Node.js
- Express.js
- MongoDB Atlas

**Tools**
- Git
- GitHub
- Render

---

## Folder Structure

```
Mo-View
│
├── frontend
│   ├── index.html
│   ├── movie.html
│   ├── index.js
│   ├── movie.js
│   └── style.css
│
├── backend
│   ├── api
│   ├── dao
│   ├── server.js
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## Getting Started

Clone the repository

```bash
git clone https://github.com/vedantyerekar/Mo-View.git
```

Go to the backend folder

```bash
cd backend
npm install
```

Create a `.env` file

```env
mongo_username=YOUR_USERNAME
mongo_password=YOUR_PASSWORD
```

Start the server

```bash
npm start
```

Open `frontend/index.html` using Live Server or any static server.

---

## Screenshots

### Home Page

> Add a screenshot here

### Reviews Page

> Add a screenshot here

---

## Future Improvements

- User authentication
- Watchlist feature
- Movie ratings
- Better search filters
- Backend integration for movie data

---

## Author

**Vedant Yerekar**

GitHub: https://github.com/vedantyerekar
