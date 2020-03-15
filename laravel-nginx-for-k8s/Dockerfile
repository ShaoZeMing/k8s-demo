FROM shaozeming/nginx1.17.8-for-k8s:v0.1.0
COPY nginx.vh.default.conf /etc/nginx/conf.d/laravel.conf
CMD ["nginx", "-g", "daemon off;"]
