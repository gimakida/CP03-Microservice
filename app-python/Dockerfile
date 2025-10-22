FROM python:3.11-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY app.py .
EXPOSE 5000
CMD ["python", "app.py"]


# FROM python:3.11-slim

# LABEL maintainer="seunome@email.com" \
#       org.opencontainers.image.title="Minha App" \
#       org.opencontainers.image.description="Aplicação " \
#       org.opencontainers.image.version="1.0.0" \
#       org.opencontainers.image.source="https://github.com/seu-usuario/seu-repo"

# ENV PYTHONDONTWRITEBYTECODE=1 \
#     PYTHONUNBUFFERED=1


# WORKDIR /app
# RUN adduser --disabled-password --gecos "" appuser \
#  && chown -R appuser /app


# COPY requirements.txt .


# RUN pip install --no-cache-dir -r requirements.txt

# COPY app.py .

# USER appuser

# EXPOSE 5000

# CMD ["python", "app.py"]
