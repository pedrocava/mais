FROM python:3.9
WORKDIR /app
ENV PYTHONPATH=/app PYTHONUNBUFFERED=1 PYTHONIOENCODING=UTF-8

RUN pip install --upgrade google-cloud-tasks
COPY main.py /app/
CMD ["python", "/app/main.py"]