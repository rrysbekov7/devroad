FROM nginx:alpine

# Копируем все файлы сайта в nginx
COPY . /usr/share/nginx/html

# Если хочешь использовать свою конфигурацию nginx (пока можно без)
# COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

# Nginx в alpine образе запускается автоматически
