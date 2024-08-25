# nginx/Dockerfile
FROM nginx:alpine

# Copia o arquivo de configuração do NGINX
COPY nginx.conf /etc/nginx/nginx.conf

# Copia o arquivo index.html para o diretório padrão do NGINX
COPY index.html /usr/share/nginx/html/index.html
