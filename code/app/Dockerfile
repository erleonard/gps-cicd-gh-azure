ARG VARIANT="3.10-bullseye"
FROM python:${VARIANT}

EXPOSE 5000
WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

#ENTRYPOINT ["python"]
# CMD ["app.py"]

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]