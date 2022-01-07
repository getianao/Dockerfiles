
# docker build -t tge/texlive:latest .
# docker run -it --name=tge-thesis-texlive  -v /data/home/tge/paper-workspace/sysu-thesis/:/workspace/sysu-thesis/ tge/texlive /bin/bash 
# docker start tge-thesis-texlive
# docker exec -it tge-thesis-texlive /bin/bash -c "cd /workspace/sysu-thesis/ && make pdf"

FROM alpine:3.10

# init environment
RUN apk add --no-cache \
    texlive-full make git

# install font
# RUN mkdir -p /usr/share/fonts/opentype
# RUN git clone https://github.com/a20185/adobefonts
# RUN chmod +x adobefonts/runner.sh
# RUN adobefonts/runner.sh
# RUN fc-cache -f -v

# CMD [ "make", "pdf" ]

