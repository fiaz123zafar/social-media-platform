# 🌟 Django Social Media Platform

<div align="center">

![Django](https://img.shields.io/badge/Django-5.0-green?style=flat-square&logo=django)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

A full-featured social media platform built with Django, featuring user authentication, posts, comments, likes, and follower system.

 · [Report Bug](#) · [Request Feature](#)

</div>


---

## ✨ Features

- 👤 **User Authentication** - Register, login, logout with secure password handling
- 📝 **Post Creation** - Share text posts with image uploads
- 💬 **Comments** - Engage with posts through comments
- ❤️ **Likes** - Like posts from other users
- 👥 **Follow System** - Follow/unfollow other users
- 📊 **User Profiles** - Customizable profiles with bio and profile pictures
- 🔒 **Admin Panel** - Manage all content through Django admin
- 📱 **Responsive Design** - Works on desktop and mobile devices

---

## 🛠️ Technologies Used

- **Backend:** Python, Django 5.0
- **Database:** SQLite (easily upgradeable to PostgreSQL)
- **Frontend:** HTML5, CSS3, JavaScript
- **Authentication:** Django built-in authentication
- **File Storage:** Django FileField for image uploads

---

## 🚀 Installation & Setup

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git

### Step 1: Clone the Repository
```bash
git clone https://github.com/fiaz123zafar/social-media-platform.git
cd social-media-platform
```

### Step 2: Create Virtual Environment

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**Mac/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### Step 5: Create Superuser
```bash
python manage.py createsuperuser
```

Follow the prompts to create an admin account.

### Step 6: Run Development Server
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

---

## 📁 Project Structure
```
SocialMediaPlatform/
├── social_project/          # Project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── social_app/              # Main application
│   ├── models.py           # Database models
│   ├── views.py            # View functions
│   ├── forms.py            # Django forms
│   ├── urls.py             # URL routing
│   └── templates/          # HTML templates
├── media/                   # User uploaded files
├── manage.py               # Django management script
└── requirements.txt        # Python dependencies
```

---

## 💡 Key Features Explained

### User Profiles
Each user has a customizable profile with:
- Profile picture
- Bio/About section
- Follower/Following count
- Post count

### Posts
Users can create posts with:
- Text content (up to 500 characters)
- Optional image upload
- Timestamp
- Edit and delete functionality

### Social Interactions
- **Likes:** One like per user per post
- **Comments:** Unlimited comments with timestamps
- **Follow System:** Users can follow/unfollow each other

---

## 🔮 Future Enhancements

- [ ] Direct messaging system
- [ ] Notifications for likes, comments, and follows
- [ ] Hashtag support
- [ ] Search functionality
- [ ] Stories feature (24-hour posts)
- [ ] Dark mode
- [ ] Email verification
- [ ] Password reset
- [ ] Real-time updates with WebSockets

---

## 📚 What I Learned

Building this project helped me learn:
- Django MVT (Model-View-Template) architecture
- User authentication and authorization
- Database relationships (One-to-Many, Many-to-Many)
- File uploads and media handling
- Form validation and security
- RESTful URL design
- Git version control

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Fiaz Zafar**

Full-stack developer passionate about building web applications with Django and Python.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fiaz-zafar-0b66a0258)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/fiaz123zafar)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fz.opsecengineer@gmail.com)

</div>

---

## Acknowledgments

- Django Documentation
- Stack Overflow Community

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ and Django

</div>

MIT License

## Author

Fiaz Zafar
