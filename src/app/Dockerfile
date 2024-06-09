FROM python:3.12

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT [ "streamlit", "run", "app.py" "--server.port", "8080"]