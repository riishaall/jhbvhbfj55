FROM python:3.10-slim
WORKDIR /app
COPY . .
EXPOSE 9776
CMD ["python","app.py"]
