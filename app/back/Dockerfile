# image Python
FROM python:3.8-slim

# directory
WORKDIR /app

# requirements import
COPY requirements.txt .

# install requirements
RUN pip install -r requirements.txt


COPY . .

# start app
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]

