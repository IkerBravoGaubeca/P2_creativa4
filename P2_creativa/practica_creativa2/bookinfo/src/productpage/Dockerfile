FROM python:3.8.10-buster
WORKDIR /app
COPY . /app

RUN pip install -r requirements.txt
RUN pip install --upgrade json2html requests urllib3 chardet

ENV GROUPO_NUMERO=30

EXPOSE 9080

CMD ["python", "productpage.py","9080"]