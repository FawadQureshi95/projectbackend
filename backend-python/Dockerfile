FROM python:3.6-alpine

RUN pip install flask

COPY backend-python/app.py /

EXPOSE 8080

CMD [ "python", "./app.py" ]
