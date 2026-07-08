# Resumify

> AI-powered resume builder that helps users create professional, ATS-friendly resumes using customizable templates and AI-generated content.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-red)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Overview

Resumify is a full-stack web application that simplifies resume creation by combining customizable templates with AI-powered content generation.

Users can securely create an account, build and manage multiple resumes, generate AI-assisted professional summaries, upload profile pictures, edit resumes anytime, and export polished PDF resumes ready for job applications.

---

## Features

- Secure user authentication and authorization
- AI-powered content generation using DeepSeek API
- Six professionally designed resume templates
- Create, edit, and manage multiple resumes
- Export resumes as high-quality PDF files
- Profile picture upload support
- Token-based free and premium usage system
- Responsive user interface
- Secure input sanitization
- Persistent resume storage using SQLite

---

## Tech Stack

### Backend

- Python
- Flask
- SQLAlchemy
- SQLite

### Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap

### AI Integration

- DeepSeek API (via OpenRouter)

### Other Tools

- Jinja2
- Bleach
- Git
- GitHub

---

## Screenshots

> *Screenshots will be added soon.*

Suggested screenshots:

- Landing Page
- Login & Registration
- Dashboard
- Resume Builder
- Template Selection
- Generated Resume

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Atrv3000/resumify.git
cd resumify
```

### Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure environment variables

Create a `.env` file in the project root and add your API credentials.

```env
OPENROUTER_API_KEY=your_api_key_here
SECRET_KEY=your_secret_key_here
```

### Run the application

```bash
python app.py
```

The application will be available at:

```
http://127.0.0.1:5000
```

---

## Project Structure

```
resumify/
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── uploads/
│
├── templates/
│   ├── auth/
│   ├── dashboard/
│   ├── resume templates/
│   └── ...
│
├── instance/
│
├── app.py
├── models.py
├── forms.py
├── config.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Future Improvements

- PostgreSQL support
- Docker containerization
- Cloud deployment
- Resume sharing via public links
- AI-powered ATS score checker
- Resume analytics
- Additional premium templates
- Multiple language support

---

## Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository, create a new branch, and submit a pull request.

---

## Author

**Atharva Bawge**

GitHub: https://github.com/Atrv3000

---

## License

This project is licensed under the MIT License.

---

If you found this project useful, consider giving it a ⭐ on GitHub.
