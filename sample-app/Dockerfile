FROM python:3.7

WORKDIR /app
COPY . /app
RUN python -m pip install -r requirements.txt

ENV PYTHONPATH=/app:/app/src

CMD ["python", "src/main.py"]