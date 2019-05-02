FROM mysql:5.7

# Install tools
RUN apt-get update
RUN apt-get install nano -y

# set timezone
ENV TZ=Asia/Jakarta
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

# Copy conf files
COPY image-files/ /

# Expose port
EXPOSE 3306

# ENTRYPOINT ["apachectl", "-DFOREGROUND"]
# CMD ["tail", "-f", "/dev/null"]