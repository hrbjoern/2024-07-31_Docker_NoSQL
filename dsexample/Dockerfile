# Start with Python 3.9:
FROM python:3.9 

RUN pip install numpy

COPY . /app 

WORKDIR /app 
# geht auch, ist besser für Python-Imports

CMD [ "python", "/app/main.py" ]
# List of tokens going to OS!