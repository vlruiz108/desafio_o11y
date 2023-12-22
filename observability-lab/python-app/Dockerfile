# Use a imagem base do Python
FROM python:3.9

# Define o diretório de trabalho no contêiner
WORKDIR /app

# Copia os requisitos da aplicação para o contêiner
COPY requirements.txt .

# Instala as dependências da aplicação
RUN pip install -r requirements.txt

# Copia o código da aplicação para o contêiner
COPY . .

# Comando para executar a aplicação
CMD ["python", "app.py"]
