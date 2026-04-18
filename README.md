 # 📚 MERN Stack Book Store

A full-stack **Book Store Management Web Application** built using the MERN Stack .
This project performs complete **CRUD operations** for managing books.

---

## 🚀 Features

* 📖 Add new books
* 🔍 View all books
* 📝 Update book details
* ❌ Delete books
* ⚡ RESTful API integration
* 🌐 Responsive frontend
* 🔗 MongoDB Atlas cloud database

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Axios
* Tailwind CSS / CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

---


## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/book-store-mern.git
cd book-store-mern
```

---

### 2️⃣ Setup Backend

```
cd backend
npm install
```

Create a `.env` file or update `config.js`:

```
PORT=5555
MONGO_URL=your_mongodb_connection_string
```

Run backend:

```
cd backend
npm run dev
```

---

### 3️⃣ Setup Frontend
(in seperate terminal)
```

cd frontend
npm run dev
```

---

## 🔗 API Endpoints

| Method | Endpoint     | Description       |
| ------ | ------------ | ----------------- |
| GET    | `/books`     | Get all books     |
| GET    | `/books/:id` | Get book by ID    |
| POST   | `/books`     | Create a new book |
| PUT    | `/books/:id` | Update a book     |
| DELETE | `/books/:id` | Delete a book     |

---

## 📦 Sample Request (POST)

```
POST /books
Content-Type: application/json

{
  "title": "Atomic Habits",
  "author": "James Clear",
  "publishYear": 2018
}
```

---

## 🧪 Testing

You can test APIs using:

* Postman
* Thunder Client (VS Code)
with the local host url
---

## 🌍 Deployment

* Frontend: Vercel / Netlify
* Backend: Render / Railway
* Database: MongoDB Atlas

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

## 🙌 Acknowledgement

* MongoDB Atlas for database hosting
* MERN Stack community

--

<img width="2880" height="1704" alt="1" src="https://github.com/user-attachments/assets/dcf58747-a359-410a-b82a-31e31fd85643" />
<img width="2880" height="1704" alt="2" src="https://github.com/user-attachments/assets/cd6fcc7b-f1c8-4ac2-81de-b01bacbd55e2" />
