<div align="right">

# 🏨 Mokaa Residence

### *Modern Hotel Management Platform*

[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**A fullstack web application for hotel management featuring suites, restaurant, and conference facilities**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [API Docs](#-api-documentation) • [Roadmap](#-roadmap)

---

</div>

## 📖 About

Mokaa Residence is a comprehensive hotel management platform that provides:

- 🛏️ **Suite Management** - Browse and book luxurious suites
- 🍽️ **Restaurant Services** - Explore dining options and menus
- 🎤 **Conference Facilities** - Book meeting and event spaces
- 🌐 **Bilingual Support** - Full French & English interface
- 📱 **Responsive Design** - Seamless experience across all devices

## ✨ Features

### Current
- 🎨 Modern, responsive UI
- 🔐 Secure authentication system
- 📊 Admin dashboard for content management
- 🌍 Bilingual interface (FR/EN)

### Coming Soon
- [ ] Real-time booking system
- [ ] Payment integration
- [ ] Email notifications
- [ ] Customer reviews & ratings
- [ ] Photo gallery
- [ ] Availability calendar

## 🚀 Tech Stack

<table>
<tr>
<td align="right" width="50%">

### Frontend
- **React** - UI Framework
- **CSS3** - Styling
- **i18next** - Internationalization
- **Axios** - API Communication

</td>
<td align="right" width="50%">

### Backend
- **Django** - Web Framework
- **Django REST Framework** - API
- **SQLite/PostgreSQL** - Database
- **JWT** - Authentication

</td>
</tr>
</table>

## 📦 Installation

### Prerequisites

- Python 3.8+
- Node.js 16+
- npm or yarn

### Backend Setup

```bash
# Navigate to backend directory
cd backend/hotel_backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# Install dependencies
pip install django djangorestframework

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start server
python manage.py runserver
```

**Backend runs on:** `http://127.0.0.1:8000`

### Frontend Setup

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

**Frontend runs on:** `http://localhost:5173`

## 📂 Project Structure

```
mokaaResidence/
├─ backend/
│  ├─ hotel_backend/          # Django project settings
│  │  ├─ settings.py
│  │  ├─ urls.py
│  │  └─ wsgi.py
│  ├─ core/                   # Main application
│  │  ├─ models.py           # Database models
│  │  ├─ views.py            # API views
│  │  ├─ serializers.py      # DRF serializers
│  │  └─ urls.py             # URL routing
│  └─ manage.py
│
└─ frontend/
   ├─ src/
   │  ├─ components/         # React components
   │  ├─ pages/             # Page components
   │  ├─ locales/           # i18n translations
   │  ├─ App.jsx
   │  └─ index.jsx
   └─ package.json
```

## 🔌 API Documentation

### Endpoints (Planned)

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/rooms/` | List all rooms |
| GET | `/api/rooms/:id/` | Get room details |
| POST | `/api/bookings/` | Create booking |
| GET | `/api/restaurant/` | Restaurant info |
| GET | `/api/conference/` | Conference facilities |

**Admin Panel:** `http://127.0.0.1:8000/admin`

## 🗺️ Roadmap

### Phase 1: Foundation ✅
- [x] Project setup
- [x] Basic structure
- [x] README documentation

### Phase 2: Core Features 🚧
- [ ] Database models
- [ ] REST API endpoints
- [ ] Frontend components
- [ ] Bilingual implementation

### Phase 3: Advanced Features 📋
- [ ] Booking system
- [ ] Payment integration
- [ ] Email notifications
- [ ] Admin dashboard enhancements

### Phase 4: Production 🎯
- [ ] Testing & QA
- [ ] Performance optimization
- [ ] Deployment
- [ ] Documentation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Nelson**

- GitHub: [@yourusername](https://github.com/yourusername)

## 📧 Contact

For any inquiries or suggestions, please reach out via:
- Email: your.email@example.com
- Project Link: [https://github.com/yourusername/mokaa-residence](https://github.com/yourusername/mokaa-residence)

---

<div align="center">

**Made with ❤️ for hospitality excellence**

⭐ Star this repo if you find it helpful!

</div>
