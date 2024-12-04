# Usando a imagem oficial do Python como base
FROM python:3.9-slim

# Definindo o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copiando os arquivos de aplicação para o diretório de trabalho
COPY . /app 

# Instalando as dependências da aplicação
RUN pip install --no-cache-dir -r requirements.txt

# Expondo a porta 5000
EXPOSE 5000

# Comando para rodar a aplicação
CMD ["python", "main.py"]
