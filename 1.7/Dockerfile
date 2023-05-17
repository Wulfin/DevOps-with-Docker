FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y curl

COPY script.sh /usr/src/app/script.sh

RUN chmod +x script.sh

CMD ["/bin/bash", "/usr/src/app/script.sh"]
