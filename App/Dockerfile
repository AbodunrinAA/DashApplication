# use python as base image
FROM python:3.6-slim

# working directory
WORKDIR /app

# add documents to working directory
ADD . /app

# open port 8050
EXPOSE 8050

# set environment name
ENV NAME OpentoAll

# run app
CMD ["python", "app.py"]
