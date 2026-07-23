FROM python:
WORKDIR /app
COPY requirements.txt .
# COPY payment.ini .
# COPY *.py .
RUN pip3 install -r requirements.txt
CMD ["uwsgi", "--ini", "payment.ini"]