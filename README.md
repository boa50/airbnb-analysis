# Installation

If you want to run inside a container with everything installed, you could build the container with the Dockerfile inside the container folder.

After this, you may run a command line like this docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/work CONTAINER_NAME

If you want to create a fresh installation, you could use an enviroment with ptyhon 3.9 and install the jupyter notebook enviroment and the libraries specified in /container/requirements.txt 

# Dataset

The dataset was obtained from the url http://insideairbnb.com/get-the-data.html. It contains data about Airbnb listings.

The data used was from Melbourne, Australia (Date Compiled - 10 April, 2021).

# Project Organization

The project consists of a single jupyter notebook (notebook.ipynb) containing all the code used.

The container folder has the necessary files to create the Docker container.

The dataset folder is where you can put the data used. You can organize the data on a folder structure like /dataset/melbourne/listings.csv
