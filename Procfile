web: gunicorn OnlineBazar.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn OnlineBazar.wsgi
timeout = 120
workers = 2
