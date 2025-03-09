FROM python:3.9 
EXPOSE 8882
ADD . .
RUN pip install psycopg2-binary flask
CMD ["python", "./payment_app.py"]