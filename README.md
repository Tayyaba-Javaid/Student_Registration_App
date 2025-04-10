# Student_Registration_App
## Requirements

   Install Python & Pip

   Install PostgreSQL

## Steps to Run Locally

### 1. Download the Repository
   
   download the ZIP file and extract it.

### 2. 🛠️ Set Up the Database (PostgreSQL)
   
   Make sure PostgreSQL is running.

   Create a database named studentdb and update credentials if needed.

   In studentproject/settings.py, confirm or update:

   DATABASES = {

       'default': {
    
           'ENGINE': 'django.db.backends.postgresql',
        
             'NAME': 'student_db',
        
           'USER': 'postgres',
        
           'PASSWORD': 'BScs123$', 
        
           'HOST': 'localhost',
        
            'PORT': '5432',
       }
   }

### 3. Apply Migrations
   
   python manage.py makemigrations

   python manage.py migrate

### 4. Run the Server
   
   python manage.py runserver

   #### To Access this app visit http://127.0.0.1:8000/
