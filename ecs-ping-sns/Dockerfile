FROM python:3.12.3-alpine
WORKDIR /app
COPY requirements.txt /requirements.txt
RUN pip install -r /requirements.txt
COPY . /app
EXPOSE 80
CMD ["python3", "app.py"]
