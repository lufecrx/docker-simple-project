# Imagem do Nginx
FROM nginx:alpine

# Remover o arquivo de configuração padrão do Nginx
RUN rm /etc/nginx/conf.d/default.conf

# Copiar o arquivo de configuração customizado principal
COPY nginx.conf /etc/nginx/nginx.conf

# Copiar os arquivos estáticos para o diretório padrão do Nginx
COPY . /usr/share/nginx/html

# Expor a porta 80
EXPOSE 80

# Comando para rodar o Nginx
CMD ["nginx", "-g", "daemon off;"]