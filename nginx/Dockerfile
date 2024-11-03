# Используем базовый образ Alpine с NGINX
FROM nginx:alpine

# Копируем конфигурационный файл nginx.conf в контейнер
COPY nginx.conf /etc/nginx/nginx.conf

# Открываем порт 80
EXPOSE 80

# Запускаем nginx в режиме демона
CMD ["nginx", "-g", "daemon off;"]
