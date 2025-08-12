# 🎓 Online Learning Management System (LMS) – Python/Django

An advanced **web-based Learning Management System** built using **Python (Django Framework)**, designed to manage online courses, learning materials, and assessments. The platform provides separate dashboards for **Admins, Instructors, and Students**, enabling a seamless e-learning experience.

---

## 🚀 Features

- **🔐 User Authentication & Role Management**  
  Secure login and registration with role-based permissions (Admin, Instructor, Student).

- **📚 Course Management**  
  Create, edit, and organize courses with multiple sections and lessons.

- **📂 Content Upload**  
  Upload videos, PDF notes, images, and downloadable resources.

- **📝 Online Assessments**  
  Create quizzes, manage assignments, and track results.

- **📊 Dashboards**  
  - **Student**: View enrolled courses, progress, and grades.  
  - **Instructor**: Manage courses, assignments, and student submissions.

- **🔍 Search & Filter**  
  Easily find courses or materials.

- **📱 Responsive Design**  
  Works on desktops, tablets, and mobile devices.

---

## 🛠️ Tech Stack

- **Backend:** Python, Django Framework  
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap  
- **Database:** SQLite / PostgreSQL (configurable)  
- **Authentication:** Django Auth System  
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

django-lms-main/
│
├── lms/ # Main project folder
├── courses/ # App for course management
├── users/ # App for authentication & roles
├── templates/ # HTML templates
├── static/ # CSS, JS, and image files
├── media/ # Uploaded files
├── db.sqlite3 # SQLite database (default)
├── manage.py # Django project manager
└── requirements.txt # Python dependencies

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Online-Learning-Management-System-Python.git
cd Online-Learning-Management-System-Python
python -m venv venv
venv\Scripts\activate   # For Windows
# source venv/bin/activate  # For macOS/Linux
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

