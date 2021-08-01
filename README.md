# Airbnb Melbourne Analysis

The Airbnb rooms' prices and ratings are some important aspects that the users observe when searching for accommodations.

Sometimes it is very difficult to compare which room has the best price compared with the benefits the room offers.

- Does the room’s type influence the price?
- Does the price correlate with the users' ratings?
- What are the variables that influence the price more?

These are some questions tried to be ansewered by this project.

In this project one of the conclusions is that the more privative the space, the prices are higher.

The regression algorithm used to analyze the features with more importance to determine the prices of the rooms was not very useful with a low R².

## Installation

If you want to run inside a container with everything installed, you could build the container with the Dockerfile inside the container folder.

After this, you may run a command line like this docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/work CONTAINER_NAME

If you want to create a fresh installation, you could use an enviroment with ptyhon 3.9 and install the jupyter notebook enviroment and the libraries specified in /container/requirements.txt 

## Dataset

The dataset was obtained from the url http://insideairbnb.com/get-the-data.html. It contains data about Airbnb listings.

The data used was from Melbourne, Australia (Date Compiled - 10 April, 2021).

If you like to run the code as it is, you have to download the listings.csv and put inside the folder /dataset/melbourne

## Project Organization

The project consists of a single jupyter notebook (notebook.ipynb) containing all the code used.

The container folder has the necessary files to create the Docker container.

The dataset folder is where you can put the data used. You can organize the data on a folder structure like /dataset/melbourne/listings.csv
