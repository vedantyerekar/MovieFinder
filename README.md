# 🎬 Mo-View

A full-stack movie discovery web application that enables users to browse popular movies, search for titles, and manage movie reviews. The application integrates the TMDB API for movie information and uses an Express.js backend with MongoDB Atlas for persistent review storage.

## ✨ Features

- Browse trending and popular movies
- Search movies by title
- View movie details
- Create, edit, and delete movie reviews
- Responsive user interface
- RESTful backend API
- MongoDB Atlas integration

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API

### Backend
- Node.js
- Express.js
- MongoDB Atlas

### Tools & Deployment
- Git
- GitHub
- Render

## 📁 Project Structure

```
Mo-View/
│
├── frontend/
│   ├── index.html
│   ├── movie.html
│   ├── index.js
│   ├── movie.js
│   └── style.css
│
├── backend/
│   ├── api/
│   ├── dao/
│   ├── server.js
│   ├── index.js
│   └── package.json
│
└── README.md
```

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/vedantyerekar/Mo-View.git
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
mongo_username=YOUR_USERNAME
mongo_password=YOUR_PASSWORD
```

Run the server:

```bash
npm start
```

### Frontend

Open `frontend/index.html` using Live Server or any static web server.

## 🔮 Future Enhancements

- User authentication
- Watchlist and favourites
- Movie ratings
- Advanced filtering
- Dark mode
- Backend proxy for TMDB API

## 👨‍💻 Author

**Vedant Yerekar**

GitHub: https://github.com/vedantyerekar
