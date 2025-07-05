# Sharks English School 🦈

This is a responsive website developed for **Sharks English School**, a language learning center.  
The site is designed for public viewing and includes admin features through Django's built-in admin panel.

---

## 🔍 Features

- 📱 Fully responsive frontend (HTML, CSS, JavaScript)
- ⚙️ Admin panel powered by Django (`/admin`)
- 👩‍🏫 Add/edit/delete teachers (with image and description)
- 📷 Upload IELTS result images (shown on the Results page)
- 🗺️ Embedded Google Map for location
- 🧼 Clean design and user-friendly layout

---

## 🛠 Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default)
- **Static files**: Handled using Django’s static system
- **Admin access**: Via Django `createsuperuser`

---

## 📁 How It Works

### Teachers Section:
- Admins can add new teachers with:
  - Full name
  - Description
  - Profile image

### IELTS Results Section:
- Admins can upload result images from the admin panel.
- These images will be shown on the public “Results” page.

---

## ⚙️ Admin Access

To access the admin panel:

```bash
python manage.py createsuperuser
