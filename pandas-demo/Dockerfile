FROM python:slim

WORKDIR /app

COPY requirement.txt .

RUN pip install -r requirement.txt

COPY pandas_demo.py .

CMD ["python", "pandas_demo.py"]