# Creazione immagine con servizio docker

Questa immagine potrebbe tornare utile per creazione swarm locale.
È necessario aver generato docker-base in locale.

## Per il build dell'immagine

docker build -f docker.Dockerfile -t docker-locale/docker .

## Per lanciare il container

docker run -id docker-locale/docker bash