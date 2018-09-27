FROM mysql:5.7

# Timezone settings
ARG TZ=Asia/Seoul
ENV TZ ${TZ}
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone && chown -R mysql:root /var/lib/mysql/

LABEL key="cherrypick <xotrs1@gmail.com>" 

EXPOSE 3306

