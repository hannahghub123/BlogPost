# Blog Application  

A simple blog application built using Django/Flask.  

## Features  
- User authentication (registration & login)  
- Blog post management (create, update, delete)  
- Blog post model with title, content, date, and author  
- Views for listing, viewing, and managing blog posts  
- HTML templates for UI  
- Basic styling with CSS/Bootstrap  

## Installation  

1. **Clone the repository**  
   git clone <your-repo-url>
   cd <project-directory>
2. **Set up a virtual environment**
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
3. **Install dependencies**
    pip install -r requirements.txt
4. **Run database migrations**
    python manage.py migrate   # For Django
    flask db upgrade           # For Flask (if using Flask-Migrate)
5. **Create a superuser** (Django only, optional)
    python manage.py createsuperuser
6. **Run the application**
    python manage.py runserver   # For Django
    flask run                    # For Flask
7. **Access the application**
    Open http://127.0.0.1:8000/ (Django) or http://127.0.0.1:5000/ (Flask) in your browser.



   
