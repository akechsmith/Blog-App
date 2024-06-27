# Django Blog App

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [API Endpoints](#api-endpoints)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
This is a simple blog application built using Django. It utilizes Django's Class-Based Views (CBVs) to implement CRUD (Create, Read, Update, Delete) functionalities. The app allows users to create, read, update, and delete blog posts.

## Features
- List all blog posts
- View details of a single blog post
- Create a new blog post
- Update an existing blog post
- Delete a blog post
- User authentication and authorization
- Responsive design

## Installation
### Prerequisites
- Python 3.x
- Django 4.x
- pip

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/django-blog-app.git
   cd django-blog-app
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Run database migrations:**
   ```bash
   python manage.py migrate

5. **Create a superuser:**
   ```bash
   python manage.py createsuperuser

6. **Run the development server:**
   ```bash
   python manage.py runserver

7. **Access the application:**
   Open your browser and navigate to `http://127.0.0.1:8000`

## Configuration
### Settings
Before running the app, you may need to configure some settings in settings.py:

- Database: Configure your database settings.
- Static and Media Files: Ensure paths for static and media files are correctly set.
- Security: Set DEBUG to False in a production environment and configure allowed hosts.
### Environment Variables
You may use a .env file to manage environment-specific variables. Use the django-environ package to load these variables in your settings.py.
## Usage
### Running the Development Server
To run the development server, use:
```bash
   python manage.py runserver

```
Navigate to http://127.0.0.1:8000 to access the application.

### Admin Interface
Access the Django admin interface at http://127.0.0.1:8000/admin using the superuser credentials created earlier.

### Creating and Managing Blog Posts
- Create Post: Navigate to /posts/create/ to create a new blog post.
- List Posts: Navigate to /posts/ to see a list of all blog posts.
- Detail View: Click on a post title in the list to see its details.
- Update Post: In the detail view, click the "Edit" button to update the post.
- Delete Post: In the detail view, click the "Delete" button to delete the post.
## Contributing
//
## License

MIT License

Copyright (c) 2040 NotNow

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

