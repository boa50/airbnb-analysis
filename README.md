#Installation
If you want to run inside a container with everything installed, you could build the container with the Dockerfile inside the container folder.
After this, you may run a command line like this docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/work CONTAINER_NAME

#Dataset
The dataset was obtained from the url http://insideairbnb.com/get-the-data.html.
It contains data about Airbnb.
The data used was from Melbourne, Australia (Date Compiled - 10 April, 2021) and Sydney, Australia (Date Compiled - 10 April, 2021).
