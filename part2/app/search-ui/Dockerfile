FROM python:3.10
RUN pip install elasticsearch streamlit==1.20.0

WORKDIR /app
COPY search-ui/ .
COPY es_query.py .

EXPOSE 8501

CMD ["streamlit", "run", "app.py"]
