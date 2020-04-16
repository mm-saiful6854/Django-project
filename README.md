# Django-project
Some projects are used to learn django framework

# Django Database setup, postgresql:
  ### 1. create database in pgadmin panel
  ### 2. connect application with that created database
          DATABASES = {
            'default': {
              'ENGINE': 'django.db.backends.postgresql',
               'NAME': 'EcDB',
               'USER': 'postgres',
               'PASSWORD': '',
               'HOST': 'localhost'
              }
          }
  #### 2.1 some basic setup
         pip install psycopg2
         
         this package is the adapter of postgresql to connected with application
  ### 3. create class inhereted models.Model 
         For example: 
  ### 4. create migration file
         pip install pillow
         python manage.py makemigrations
  ### 5. sqlmigrate to database
         python manage.py sqlmigrate [appname] version(e.g. 0001)
  ### 6. migrate to database
         python manage.py migrate
