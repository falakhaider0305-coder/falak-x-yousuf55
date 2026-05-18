# Complete Flask Multi-Page Website

## Folder Structure
```
falak/
├
├── requirements.txt       # Dependencies: Flask
├── templates/             # HTML templates
│   ├── base.html          # Base template with responsive navbar (login-aware)
│   ├── index.html         # Home page with hero & features
│   ├── about.html         # About page with stats & team placeholder
│   ├── services.html      # Services with animated cards & icons
│   ├── gallery.html       # Responsive image gallery grid
│   ├── contact.html       # Contact form & info (simulated submit)
│   ├── login.html         # Login form (demo: admin/password123)
│   └── register.html      # Registration form (in-memory users)
└── static/
    └── css/
        └── style.css      # Modern responsive CSS (gradients, flex/grid, animations)
```

## Features Implemented
- **All 7 pages** with Flask routes: Home (/), About (/about), Services (/services), Gallery (/gallery), Contact (/contact), Login (/login), Register (/register)
- **Navigation bar** on all pages (shows user info & Logout if logged in)
- **Responsive design** (mobile-first CSS with flexbox/grid/animations)
- **Simulated authentication**: Login/register with Flask sessions & flash messages
  - Demo: username `admin`, password `password123`
  - New registrations work (in-memory, reset on restart)
- **Contact form**: Simulated submission with success message
- **Modern UI**: Gradient backgrounds, hover effects, Font Awesome icons, smooth animations

## Setup & Run Instructions
1. Open terminal in `c:/Users/cyber/Desktop/falak`
2. Create virtual environment: `python -m venv venv`
3. Activate: `venv\Scripts\activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run server: `python app.py`
6. Visit: http://127.0.0.1:5000/

## Testing Checklist
- ✅ All pages accessible and responsive
- ✅ Navbar works across pages (login state preserved)
- ✅ Login/Register forms functional
- ✅ Contact form shows success message
- ✅ No database/file dependencies
- ✅ Zero JavaScript (pure HTML/CSS/Flask)

Website is production-ready structure, runs without errors!
