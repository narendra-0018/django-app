FROM python:3
RUN pip install django==3.2
RUN pip install django-crispy-forms
RUN pip install pillow
RUN pip install javascript
RUN pip install crispy-bootstrap4

COPY . .

#RUN python3 manage.py migrate
EXPOSE 8001
CMD ["python3","manage.py","runserver","0.0.0.0:8001"]
