FROM python:3


RUN mkdir /app
WORKDIR /app

COPY requirements.txt .
#RUN pip freeze > requirements.txt
RUN pip install -r requirements.txt

EXPOSE 8000
ENTRYPOINT ["python","app.py"]