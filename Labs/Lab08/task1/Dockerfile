FROM ubuntu
LABEL maintainer="sidraobaid1279@gmail.com"
COPY myfile /app/
RUN echo "my text" >> /app/myfile
ADD https://www.python.org/static/community_logos/python-logo.png /app/
WORKDIR /app
CMD ["cat", "myfile"]
