FROM bitnami/python:3.8.13

RUN pip install cassandra-driver
RUN pip install flask
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0

EXPOSE 3000
COPY . .
CMD ["python","app.py"]