FROM python:3.9-alpine

COPY . ./
WORKDIR /django/littlepolls/
RUN pip install django

CMD ["python", "manage.py", "runserver", "0.0.0.0:80"]
