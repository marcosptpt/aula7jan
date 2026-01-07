# Imagem base
FROM python:3.11-slim

# Diretório da aplicação
WORKDIR /app

# Copiar arquivos
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# Expõe a porta
EXPOSE 5000

# Comando para rodar a aplicação
CMD ["python", "app.py"]