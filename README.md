# Instagram Backend Clone

A backend API for an Instagram-like application built with **Python** and **FastAPI**.  
This project includes user authentication, posts, likes, comments, and other core social media features.

---

## 🚀 Features
- User Registration & Authentication (JWT-based)
- Profile Management (username, bio, profile picture)
- Create, Read, Update, Delete (CRUD) Posts
- Like & Comment System
- Follow / Unfollow Users
- News Feed (posts from followed users)
- Secure Password Hashing
- RESTful API Endpoints

---

## 🛠️ Tech Stack
- **Backend Framework**: FastAPI   
- **Database**: SQLite  
- **Authentication**: JWT (JSON Web Token)  
- **ORM**: SQLAlchemy  

---

## ⚙️ Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/instagram-backend.git
   cd instagram-backend
   
2. **Create Virtual Environment**
   
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3. **Install Dependencies**
   
pip install -r requirements.txt

4. **Setup Database**
   
Update database URL in config.py

5. **Run the Server**
    
uvicorn main:app --reload   # FastAPI

6. **API Documentation**
    
Swagger UI: http://127.0.0.1:8000/docs

---

**Future Improvements**

Direct Messaging (DMs)

Stories & Highlights

Notifications System

Media Uploads to Cloud Storage (AWS S3 / Cloudinary)

---

**Contributing**

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.


