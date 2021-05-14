FROM ubuntu:18.04

COPY script.sh .

RUN apt-get update -y

RUN apt install curl -y

CMD echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;

## run with command sudo docker run -it curler