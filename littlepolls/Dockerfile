FROM python:3.9-slim

COPY . ./
WORKDIR /django/littlepolls/
RUN pip install django
ENV PORT=8000
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
