FROM python:3.11-slim

WORKDIR /app

COPY shared-lib /shared-lib
COPY project-a /app

RUN pip install /shared-lib
RUN pip install -r requirements.txt

CMD ["python", "app.py"]
