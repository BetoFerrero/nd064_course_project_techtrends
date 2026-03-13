# Prerequisites
FROM python:3.8-alpine
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
# Initialization
EXPOSE 3111
RUN python init_db.py
CMD ["python","app.py"]
