FROM nginx:latest


COPY nginx.conf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf

CMD ["nginx","-g","daemon off;"]
