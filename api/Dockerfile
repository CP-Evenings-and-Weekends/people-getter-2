FROM python:3.11-bookworm

WORKDIR /src

COPY requirements.txt ./

RUN pip install -r requirements.txt

COPY server.py db_ip_addr ./

CMD ["python", "server.py"]
