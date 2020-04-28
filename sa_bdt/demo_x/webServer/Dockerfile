FROM python:latest 
COPY ./code /code
WORKDIR /code
COPY requirements.txt /src/
RUN pip install -r /src/requirements.txt
CMD ["python", "app.py"]
