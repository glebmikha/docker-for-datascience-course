docker exec -it 1b7ab9790fc7 bash

docker cp wine.data 1b7ab9790fc7:/home/jovyan/wine.data

docker run -v /Users/glebmikh/Desktop/docker:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca

docker build -t my_notebook .

docker run -v /Users/glebmikh/Desktop/docker:/home/jovyan/ -p 8888:8888 my_notebook

docker-compose up