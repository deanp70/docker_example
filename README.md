# Commands Run for the Purpose of this Tutorial
1. `vi Dockerfile`
1. `vi run_jupyter.sh`
1. `mkdir docker_fs`
1. `sudo docker build -t tutorial -f ./Dockerfile ./`
1. `docker run --rm -it --name y-data -p 7745:7745 -v "/${PWD}/docker_fs/:/ds" tutorial`
