FROM nginx:latest
WORKDIR /usr/share/nginx/html
ADD . .
RUN chmod +x hostname.sh 
RUN chmod +x index.sh 
CMD ["./hostname.sh"]