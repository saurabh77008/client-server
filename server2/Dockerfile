# Server 2 Dockerfile
FROM python:3.8-slim

WORKDIR /app

COPY server2.py /app

RUN pip install flask flask_cors

EXPOSE 8001

CMD ["python", "server2.py"]
