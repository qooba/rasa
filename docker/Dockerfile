FROM rasa/rasa:1.7.0
USER root
RUN apt update && apt install curl git cmake ack g++ python3-dev vim-youcompleteme -yq
RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/qooba/vim-python-ide/master/setup.sh)"
ENTRYPOINT /bin/bash
