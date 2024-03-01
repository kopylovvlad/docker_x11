FROM debian:latest

# FIREFOX AND GNOME
RUN apt update && apt install -y firefox-esr task-gnome-desktop gdm3

CMD /usr/bin/firefox

# docker build -t gnome .
# docker run --rm -it -e DISPLAY="${IP}:0" gnome
# docker run --rm -it -e DISPLAY="${IP}:0" gnome bash
# ls -l /usr/bin/ | grep gnome
