FROM python:3.12.7

WORKDIR /usr/local/src/app
COPY . .

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 80

CMD ["python", "main.py"]
