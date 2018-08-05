# Pull base image
FROM python:3.6-slim

# Set work directory
RUN mkdir /code
WORKDIR /code

# Include the project and install dependencies
ADD . /code/
CMD "pip install --upgrade pip && pip install -r requirements.txt"

