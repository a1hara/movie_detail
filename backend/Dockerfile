# backend/Dockerfile

FROM python:3.9.16

WORKDIR /code

COPY requirements.txt /code/

RUN pip install --no-cache-dir -r requirements.txt

COPY . /code

CMD ["python", "app.py"]
