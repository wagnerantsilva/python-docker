# Exemplo de aplicação Python rodando em Docker

Código de exemplo para o vídeo sobre aplicações Python em Docker.

Caso não tenha visto, segue o link:

https://www.youtube.com/watch?v=WRJDGo0HWng&feature=youtu.be

Keep hacking :-)

comando:
docker run -it --rm --name my-running-script -v "$PWD":/usr/src/code -w /usr/src/code python:3 python app.py
