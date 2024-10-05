# Imagem base do Python
FROM python:3.9

# Diretorio de trabalho dentro do container
WORKDIR /app

# Instalar as dependencias
COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

# Copiar o código fonte para o container
COPY . .

# Variaveis de ambiente 
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_RUN_PORT=5000

# Expor a porta 5000
EXPOSE 5000

# Comando para rodar a aplicação
CMD ["python", "app.py"]