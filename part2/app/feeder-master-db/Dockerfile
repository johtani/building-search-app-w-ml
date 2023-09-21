FROM python:3.10
RUN pip install elasticsearch

WORKDIR /app

ADD dataset/simplewiki-202109-pages-with-pageviews-20211001.bz2 .

COPY feeder-master-db/ .
