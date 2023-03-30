# syntax=docker/dockerfile:1
FROM python:3.7.7-slim-buster
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY . .
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]

# python3 -m pip freeze > requirements.txt   -- copies the requerments to the txt file
#docker build --tag dockerapp .              -- build docker
#docker run -d -p 8000:5000 dockerapp        -- run docker
