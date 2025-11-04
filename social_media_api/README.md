# Social Media API

A Django-based RESTful API for a social media platform, built as part of the ALX Django learning lab.

##  Features

- User registration and authentication  
- Profile management  
- Create, retrieve, update, and delete posts  
- Like and comment on posts  
- (Add/remove features as per your implementation)

##  Technology Stack

- Python  
- Django  
- Django REST Framework (DRF)  
- SQLite (default) or any preferred relational database  

##  Setup & Installation (Local)

1. Clone the repository:

   ```bash
   git clone https://github.com/kerolosnady2/Alx_DjangoLearnLab.git
   cd Alx_DjangoLearnLab/social_media_api
Create and activate a virtual environment:
python3 -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate

Install dependencies: pip install -r requirements.txt

Apply database migrations: python manage.py migrate

Run the development server: python manage.py runserver

Access the API at http://127.0.0.1:8000/

API Endpoints:
POST /api/register/ – Register a new user

POST /api/login/ – Obtain authentication token

GET /api/profile/ – Retrieve user profile

POST /api/posts/ – Create a post

GET /api/posts/ – List posts

POST /api/posts/{id}/like/ – Like a post

POST /api/posts/{id}/comment/ – Comment on a post
(Adjust endpoints based on actual URL patterns and features)
