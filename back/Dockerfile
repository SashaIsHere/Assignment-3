FROM python:3.6

RUN apt-get update
WORKDIR /app
EXPOSE 3000
COPY . .
RUN pip install -r requirements.txt

CMD python back.py
