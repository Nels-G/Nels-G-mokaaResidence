<div align="left">

# 🏨 Mokaa Residence

### *Hotel Management Platform*

[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Private project - Fullstack web application for hotel management**

---

</div>

## 📖 About

Mokaa Residence is a custom hotel management platform developed for a private client, featuring:

- 🛏️ **Suite Management** - Browse and book luxurious suites
- 🍽️ **Restaurant Services** - Explore dining options and menus
- 🎤 **Conference Facilities** - Book meeting and event spaces
- 🌐 **Bilingual Support** - Full French & English interface
- 📱 **Responsive Design** - Seamless experience across all devices

## 🚀 Tech Stack

<table>
<tr>
<td align="left" width="50%">

### Frontend
- **React** - UI Framework
- **CSS3** - Styling
- **i18next** - Internationalization
- **Axios** - API Communication

</td>
<td align="center" width="50%">

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

## ✨ Features Development

### Phase 1: Foundation ✅
- [x] Project setup
- [x] Basic structure
- [x] Documentation

### Phase 2: Core Features 🚧
- [ ] Database models
- [ ] REST API endpoints
- [ ] Frontend components
- [ ] Bilingual implementation

### Phase 3: Advanced Features 📋
- [ ] Booking system
- [ ] Payment integration
- [ ] Email notifications
- [ ] Admin dashboard

### Phase 4: Deployment 🎯
- [ ] Testing & QA
- [ ] Performance optimization
- [ ] Production deployment
- [ ] Client handover

## 🔒 Security Notes

- Keep `.env` files private and never commit them
- Update `SECRET_KEY` in production
- Configure `ALLOWED_HOSTS` for production
- Use HTTPS in production
- Regular dependency updates

## 📝 Development Guidelines

### Code Style
- Follow PEP 8 for Python code
- Use ESLint for JavaScript/React
- Write clear commit messages
- Document complex functions

### Git Workflow
- Create feature branches for new features
- Use meaningful branch names
- Keep commits atomic and focused
- Test before committing

## 🛠️ Useful Commands

### Django
```bash
python manage.py makemigrations    # Create migrations
python manage.py migrate           # Apply migrations
python manage.py createsuperuser   # Create admin user
python manage.py runserver         # Start dev server
python manage.py shell             # Django shell
```

### React
```bash
npm run dev        # Start development server
npm run build      # Build for production
npm run preview    # Preview production build
```

## 👨‍💻 Developer

**Nelson**

For project-related questions or issues, please contact the project manager.

---

<div align="center">

**Private & Confidential** • © 2025 Mokaa Residence

</div>=
