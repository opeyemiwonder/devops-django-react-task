FROM  python:3

ENV PYTHONUNBUFFERED=1

WORKDIR /api

COPY requirements.txt requirements.txt

# RUN pip3 install -r requirements.txt
RUN pip install django django-cors-headers

COPY . .

EXPOSE 8000

CMD [ "python3", "manage.py", "runserver"]