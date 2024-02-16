FROM debian
RUN apt update && apt install -y apache2
ENTRYPOINT [ "apachectl", "-D", "FOREGROUND" ]