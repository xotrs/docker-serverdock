FROM nginx:latest

COPY nginx.conf /etc/nginx/
COPY ssl /etc/nginx/
COPY conf.d/cherrypick.co.kr.conf /etc/nginx/conf.d/

ENV TZ=Asia/Seoul
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

LABEL key="cherrypick <xotrs1@gmail.com>" 

EXPOSE 443

