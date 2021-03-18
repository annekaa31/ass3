FROM python:3.6
RUN apt-get update
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY back.py .
CMD python back.py
EXPOSE 3000
