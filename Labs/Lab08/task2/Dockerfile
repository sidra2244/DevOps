FROM ubuntu
LABEL maintainer="sidraobaid1279@gmail.com"
RUN apt-get update && apt-get install -y python3
ENV PAGE_TITLE="Hello from Lab 8"
COPY index.html /app/
WORKDIR /app
RUN sed -i "s/PAGE_TITLE/$PAGE_TITLE/g" index.html
EXPOSE 3000
CMD ["python3", "-m", "http.server", "3000", "--bind", "0.0.0.0"]
