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


