
# Blog API Project



1. **Admin Interface:**

    The project includes an administration interface accessible at "/admin/". This is a standard Django admin interface for managing site content and configurations.

2. **API Endpoints:**
   
    The main API endpoints are structured under "/api/v1/" and are included from the "posts.urls" module. This suggests that the project has functionalities related to posts or similar entities.

3. **Authentication Endpoints:**
   
    Authentication-related endpoints are provided under "/api-auth". These include routes for integrating the Django Rest Framework's authentication views.

4. **dj-rest-auth and Registration Endpoints:**
   
    Additional authentication-related endpoints are included under "/api/v1/dj-rest-auth/" and "/api/v1/dj-rest-auth/registration/". These endpoints are likely associated with the `dj_rest_auth` and `dj_rest_auth.registration` modules, handling user authentication and registration.

5. **API Schema Documentation:**
   
    The project incorporates schema documentation using the `drf_spectacular` library. The API schema is available at "/api/schema", and interactive documentation can be accessed via Redoc at "/api/schema/redoc/" and Swagger UI at "/api/schema/swagger-ui/".

In summary, this Django project serves as a backend for an API-driven web application, featuring an admin interface for content management, various API endpoints for posts and authentication, and comprehensive API schema documentation using the `drf_spectacular` library. The inclusion of Redoc and Swagger UI enhances the project's usability by providing interactive API documentation.


## Run Locally

Clone the project

```bash
  git clone https://github.com/Jishnu-k-b/Blog-django.git
```

Go to the project directory

```bash
  cd Blog-django
```
Create and activate virtual environment

```bash
  python -m venv .venv

  .venv\Scripts\activate
```

Install dependencies

```bash
  python -m pip install -r requirements.txt
```

Start the server

```bash
  python manage.py runserver
```

