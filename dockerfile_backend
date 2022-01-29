FROM python:3.8
WORKDIR /app
COPY ./api/requirements.txt .
COPY ./api/app.py .
RUN pip3 install -r requirements.txt
COPY . .
EXPOSE 8000
CMD ["gunicorn","-b","0.0.0.0:8000","app:app"]
