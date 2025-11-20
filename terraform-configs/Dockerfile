FROM python:latest

WORKDIR /app

COPY terraform-configs/app.py .

RUN pip install flask

EXPOSE 8080

CMD [ "python", "app.py" ]