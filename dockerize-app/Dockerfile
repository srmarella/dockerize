# Dockerfile, Image, Container 
FROM python:3.9

ADD main.py .

RUN pip install requests beautifulsoup4

CMD [ "python", "./main.py" ]

# docker commands 
# docker -v
# docker build -t python-imdb .
# docker run python-imdb:latest
# docker run -t -i python-imdb:latest   # because we are doing input add -t  -i, -t: sudo terminal & -i interactive mode

