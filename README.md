## End to End MAchine Learning Project

## for aws deployment
->add .ebextensions folder-> python.config -> 
option_settings:
  "aws:elasticbeanstalk:container:python":
    WSGIPath: application:application

->rename app.py to application.py


by default flask cli expects app:app or application:app or wsgi:app