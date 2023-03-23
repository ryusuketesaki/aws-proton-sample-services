FROM python:3.12.0a5-buster
COPY app.py requirements.txt ./
RUN pip install -r requirements.txt
EXPOSE 80
CMD [ "python", "app.py"]
