FROM python:3.9
WORKDIR /app
COPY requirements.txt server.py vllm_model.py /app/
RUN pip install --no-cache-dir --upgrade -r requirements.txt

CMD ["fastapi", "run", "server.py", "--port", "80"]
