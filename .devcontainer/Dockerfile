FROM racket/racket

RUN raco pkg install --auto racket-langserver

RUN apt-get update && apt-get install -y xvfb

RUN echo 'export FONTCONFIG_PATH=/etc/fonts' >>~/.bashrc
