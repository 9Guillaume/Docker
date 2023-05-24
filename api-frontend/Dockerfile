FROM python:2.7

WORKDIR /app

COPY api.py /app/api.py

RUN pip install requests flask

ENV API_BACKEND_URL=api-backend
ENV API_BACKEND_PORT=8001

CMD ["python", "api.py"]
