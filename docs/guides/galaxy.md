# The Galaxy Platform  

<!-- ![Galaxy logo](media/galaxy_logo.png) -->


Galaxy is a web platform for bioinformatics analysis. The platform has the capability to run complex workflows in a user-friendly interface, making it suitable for both beginners and more advanced users. 

## Which Galaxy should I use? 

- There are many different Galaxy servers - each one has a different web address.
    
- For researchers based in Melbourne, Australia, we recommend you use [Galaxy-Mel](https://galaxy-mel.genome.edu.au/galaxy/).

- The main worldwide Galaxy server is [https://usegalaxy.org/](https://usegalaxy.org/)

- Other Galaxy servers are listed [here](https://galaxyproject.org/public-galaxy-servers/).

- Check the policy for the server you are using so that you know how long your data will be kept. 

- If you use more than one Galaxy server (e.g. Galaxy-Mel and useGalaxy.org) you need to register and log in separately for each server. They don't talk to each other. 

## Tutorials

To get started, try: 

* [Introduction to Galaxy](../tutorials/galaxy_101/galaxy_101.md) 
* [Galaxy Workflows](../tutorials/galaxy-worklows/galaxy-workflows) 
* Many of our other tutorials also use Galaxy, such as [RNA-seq](../tutorials/rna_seq_dge_basic/rna_seq_basic_tutorial.md) and [variant calling](../tutorials/variant_calling_galaxy_1/variant_calling_galaxy_1.md). 

## Galaxy Training Network

The Galaxy Training Network hosts a large collection of useful training material at [galaxyproject.org/learn](https://galaxyproject.org/learn/). These tutorials run on the [usegalaxy.org server](https://usegalaxy.org/).

## Running your own Galaxy server in the cloud

It is possible to run your own Galaxy instance using the Nectar cloud. 

- [Tutorial to launch your own Galaxy](../tutorials/gvl_launch/gvl_launch.md)

- [Nectar: https://nectar.org.au](https://nectar.org.au/about/)

## Running Galaxy locally using Docker

It is usually preferable to use a docker Galaxy image rather than installing Galaxy itself locally, to limit issues with tool dependencies. 

- You would need to have Docker installed: see the [Docker page](https://www.docker.com/).

- Try the [Docker tutorial](../tutorials/docker/docker.md).

- The docker container for Galaxy is at [https://hub.docker.com/r/bgruening/galaxy-stable/](https://hub.docker.com/r/bgruening/galaxy-stable/)

- To run:
    - Open a terminal window. 
    - Type `docker run -p 80:80 bgruening/galaxy-stable`
    - In a web browser, enter "localhost" in the address bar.
    - Your Galaxy should now be running. 

- To close the container:
    - Open a new terminal window.
    - Type `docker ps` to show running containers.
    - Find the container ID.
    - Type `docker stop <CONTAINER ID>`




















