# Server 1 Dockerfile
FROM python:3.8-slim

WORKDIR /app

COPY server1.py /app

RUN pip install flask flask_cors

EXPOSE 8000

CMD ["python", "server1.py"]
