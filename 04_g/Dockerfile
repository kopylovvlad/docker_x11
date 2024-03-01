FROM debian:latest

RUN apt update && apt install -y gimp
CMD /usr/bin/gimp

# docker build -t gimp .
# docker run -it -e DISPLAY="${IP}:0" --volume ~/Downloads:/home gimp /usr/bin/gimp
