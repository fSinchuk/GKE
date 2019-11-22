FROM python:3.5

COPY . /app
WORKDIR /app

RUN pip install -r requierments.txt

CMD ["python", "-u", "server.py"]