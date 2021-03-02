FROM python:3.8-slim

RUN pip install --no-cache-dir requests
RUN pip install --no-cache-dir lxml

ENTRYPOINT ["python3", "./script/parser.py"]