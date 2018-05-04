FROM ubuntu:latest
RUN apt-get update -y 
RUN apt-get install postgresql-client -y
RUN apt-get install python-minimal -y
RUN apt install python-pip -y
RUN pip install --user pipenv
RUN python -m site --user-base
RUN echo 'export PATH="$HOME/.local/bin:$PATH"'