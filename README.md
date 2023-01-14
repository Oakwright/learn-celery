# learn-celery
Learning celery and how to use it in Django

https://docs.celeryq.dev/en/stable/getting-started/first-steps-with-celery.html

Celery is the task manager

Requires a broker to pass messages around. Potential broker options:

* Redis
* RabbitMQ
* SQS

Redis is more prone to data loss on system failure. 
RabbitMQ is more prone to problems at large scale. 
SQS is AWS specific.

Requires a backend to store persisten data. Potential backend options:

* Redis
* RabbitMQ
* SQLAlchemy -> Postgres

It is common to use RabbitMQ as broker and Redis as backend together.

https://docs.celeryq.dev/en/stable/django/first-steps-with-django.html

https://github.com/celery/django-celery-beat
https://github.com/celery/django-celery-results
https://github.com/celery/librabbitmq
https://github.com/celery/celery/tree/main/examples/django
https://github.com/celery/celery/wiki


https://github.com/czue/celery-progress
https://buildwithdjango.com/projects/celery-progress/
https://github.com/eeintech/django-celery-progress-demo

https://eeinte.ch/stream/progress-bar-django-using-celery/

https://testdriven.io/blog/django-async-views/#celery-and-async-views

https://testdriven.io/blog/django-and-celery/
