FROM python:alpine
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r requirements.txt
EXPOSE 80
COPY . /app
CMD python app.py