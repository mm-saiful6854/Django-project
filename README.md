# Django-project
Some projects are used to learn django framework

# Django Database setup, postgresql:
   ## 1. create database in pgadmin panel
   ## 2. connect application with that created database
          DATABASES = {
            'default': {
              'ENGINE': 'django.db.backends.postgresql',
               'NAME': 'EcommerceDB',
               'USER': 'postgres',
               'PASSWORD': '123456',
               'HOST': 'localhost'
              }
          }
  ## 3. create class inhereted models.Model 
         For example: 
