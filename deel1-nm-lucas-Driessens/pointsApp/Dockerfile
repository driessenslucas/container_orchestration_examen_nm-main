FROM ghcr.io/eslih/python:3.12.0-alpine

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

CMD ["python", "app.py"]