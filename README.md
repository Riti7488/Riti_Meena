
# 📝 Django Blogging Platform

A full-stack blogging web application built using Django, designed and developed by Riti Meena. This project allows users to register, create posts, upload images, and manage blog content through a responsive and user-friendly interface.

## 🚀 Features

- User Registration & Authentication
- Create, Edit, and Delete Blog Posts
- Image Upload and Media Handling
- Admin Panel for Content Management
- Responsive UI with Bootstrap
- Form Validation and Clean Design

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite3
- **Tools:** VS Code

## 📁 Project Structure

```
.
├── db.sqlite3           # SQLite database
├── media/               # Uploaded images (ignored in Git)
├── venv/                # Virtual environment (ignored)
├── .gitignore           # Git ignore rules
├── <your Django app>/   # Django application logic
└── manage.py            # Django CLI tool
```

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Riti7488/YourRepoName.git
cd YourRepoName
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the server

```bash
python manage.py runserver
```

Open your browser at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## 🔐 Admin Access

To use the admin panel, create a superuser:

```bash
python manage.py createsuperuser
```

## 👩‍💻 About the Developer

**Riti Meena**  
Aspiring Computer Science Engineer with a Minor Degree in AI & ML.  
Proficient in Python, Django, and Web Development.  
Interested in AI, Machine Learning, and real-world tech applications.

## 📝 License

This project is licensed under the [MIT License](LICENSE), unless stated otherwise.
