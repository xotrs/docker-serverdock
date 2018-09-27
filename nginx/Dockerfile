FROM nginx:latest

COPY nginx.conf /etc/nginx/
COPY ssl /etc/nginx/
COPY conf.d/cherrypick.co.kr.conf /etc/nginx/conf.d/

LABEL key="cherrypick <xotrs1@gmail.com>" 

EXPOSE 443

