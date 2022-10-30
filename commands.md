# Python env

## Permite crear un entorno virtual en windows

python3 venv .venv

cd .venv/Scripts/activate

## Permite crear un fichero requirements.txt

pip3 freeze > requirements.txt

# Docker commands

## Permite construir a partir de un Dockerfile una imagen
docker build --tag {nombre de la imagen} .

### De forma abreviada:

docker build -t {nombre de la imagen}

## Construir imagen de docker de una imagen exponiendo por un puerto dado

docker run -d -p {port}:{port} {imagen}

## Subir una imagen a docker hub

docker tag {nombre de la imagen} {username cuenta docker hub}/{nombre de la imagen}

docker push {username cuenta docker hub}/{nombre de la imagen}

## Bajar imagen del repositorio de docker hub

docker pull {username cuenta docker hub}/{nombre de la imagen}