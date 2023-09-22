FROM python:3.10

RUN pip install matplotlib 'xgboost<2' scikit-learn elasticsearch

ADD dataset/simplewiki-202109-pages-with-pageviews-20211001.bz2 .

COPY workspace/ .
COPY es_query.py .
