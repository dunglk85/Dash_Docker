FROM python:3.9-slim-bullseys
WORKDIR usr/src/Dash
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .