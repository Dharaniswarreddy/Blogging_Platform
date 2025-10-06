
# Blogging Platform

A simple yet powerful blogging platform built using **Python**, **Django**, and **HTML**. This project allows users to create, manage, and share blog posts with an intuitive web interface.

## Features

- User authentication (sign up, login, logout)
- Create, edit, and delete blog posts
- List and view blogs with detailed pages
- Responsive HTML templates for user-friendly navigation
- Django-powered admin panel for content management

## Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML (with Django templating)

## Getting Started

### Prerequisites

- Python 3.x
- pip (Python package manager)
- Virtualenv (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dharaniswarreddy/Blogging_platform.git
   cd Blogging_platform
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the requirements**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (for admin access)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. Open your browser and visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Usage

- Register a new user or log in with your credentials.
- Create and manage your posts from the dashboard.
- Admin users can moderate content via the Django admin panel at `/admin/`.

## Project Structure

```
Blogging_platform/
├── blogging/           # Main app containing models, views, urls, templates
├── Blogging_platform/  # Project configuration (settings, urls, wsgi)
├── templates/          # HTML templates
├── static/             # Static files (if used)
├── manage.py
└── requirements.txt
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Developed with [Django](https://www.djangoproject.com/) and [Python](https://www.python.org/)
```
