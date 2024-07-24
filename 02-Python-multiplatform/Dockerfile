FROM python:alpine3.20
WORKDIR /app
COPY manifest.json /app/
RUN pip install flask
COPY . .
EXPOSE 5000
CMD ["python","/app/main.py"]
