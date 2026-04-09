FROM python:3.11-slim

WORKDIR /app	

COPY Project5 /app

COPY . .

COPY requirements.txt  .
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8090

CMD ["python", "Project5/server_xorkeesign.py"]