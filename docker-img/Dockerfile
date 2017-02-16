# Using official python runtime base image
FROM python:3.3.6-wheezy

# Set the application directory
WORKDIR /app

RUN apt-get update
RUN pip install twisted

ADD main.py /app/main.py

CMD ["python", "main.py"]
