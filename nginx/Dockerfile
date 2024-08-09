# Usamos la imagen oficial de Nginx como base
FROM nginx:alpine

# Copiamos el archivo de configuración de Nginx
COPY nginx.conf /etc/nginx/nginx.conf

# Exponemos el puerto 80
EXPOSE 80

# Comando para iniciar Nginx
CMD ["nginx", "-g", "daemon off;"]
