FROM python:3.8-slim-buster
WORKDIR /app
COPY . /app

RUN apt update -y
##&& apt install awscli -y
## apt-get update && apt-get install ffmpeg libsm6 libxext6 unzip -y && 
RUN apt-get update && pip install -r requirements.txt
CMD ["python3", "app.py"]