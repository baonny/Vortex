FROM python:3.12
ENV PYTHONNUNBUFFERED 1
WORKDIR /app
COPY requirementsz.txt /app/requirements.txt
RUN pip install -r requirements.txt
COPY . /app

CMD 'python manage.py runserver 0.0.0.0:8000'