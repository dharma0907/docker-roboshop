FROM  python:3.9.25-alpine3.22
WORKDIR /app
COPY requirements.txt .
COPY payment.ini .
COPY *.py .
RUN pip3 install -r requirements.txt
CMD ["uwsgi", "--ini", "payment.ini"]