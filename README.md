# 🔐 AuthSite

AuthSite is a basic Django authentication project that allows users to **log in**, access a **protected home page**, and **log out** securely.  
It is designed as a practice project to **familiarize with Django and Git workflows**.

---

## 🚀 Features
- User authentication with Django’s built-in auth system
- Login page with username and password
- Protected home page (only visible after login)
- Logout redirects back to login page
- Bootstrap-based modern UI


## 🛠️ Tech Stack
- **Python 3.10+**
- **Django 5.x**
- **Bootstrap 5** (for UI)
- **SQLite3** (default Django database)





## ⚙️ Installation & Setup

### 1. Clone Repository

git clone https://github.com/<your-username>/AuthSite.git
cd AuthSite


### 2. Create & Activate Virtual Environment


# Windows (PowerShell)
python -m venv env
.\env\Scripts\Activate.ps1



### 3. Install Dependencies


pip install -r requirements.txt


### 4. Apply Migrations


python manage.py migrate


### 5. Create Superuser (Admin Account)


python manage.py createsuperuser


👉 Enter **username**, **email (optional)**, and **password** when prompted.
This account will let you log in via `/admin/`.

### 6. Run Development Server


python manage.py runserver 8080


Visit your site at:
👉 `http://127.0.0.1:8080/login/`



## 🔑 Default URLs

* `/login/` → User login page
* `/logout/` → User logout (redirects to login)
* `/` → Protected home page (requires login)
* `/admin/` → Django admin panel (for superuser)

---

## 👨‍💻 Git Workflow Used

* Feature branches (`feature/accounts/complete_app`, `feature/ui/update_pages`)
* Meaningful commit messages following convention:

  * `feat(ui): ...` → for UI changes
  * `fix(auth): ...` → for authentication fixes
  * `chore(setup): ...` → for project setup



## 📚 Learnings & Notes

* How to set up and activate Python virtual environments
* How to configure Django apps, templates, and URLs
* Git branching workflow and pushing commits to GitHub
* Importance of excluding `env/` from Git commits
* Authentication flow in Django (Login → Home → Logout → Back to Login)

---

## 📜 License

This project is for educational purposes.
You may use and modify it freely for learning Django and Git.



✅ This README explains:  
- What **AuthSite** is  
- Project **features & tech stack**  
- Step-by-step **setup instructions** (including **superuser creation**)  
- **Git workflow** we practiced  
- **Key learnings** to remember  
