# The Galaxy Platform  

<!-- ![Galaxy logo](media/galaxy_logo.png) -->


Galaxy is a web platform for bioinformatics analysis. 

## Which Galaxy should I use? 

- There are many different Galaxy servers - each one has a different web address.
    
- For researchers based in Melbourne, Australia, we recommend you use [Galaxy-Mel](https://galaxy-mel.genome.edu.au/galaxy/).

- The main worldwide Galaxy server is [https://usegalaxy.org/](https://usegalaxy.org/)

- Other Galaxy servers are listed [here](https://galaxyproject.org/public-galaxy-servers/).

- Check the policy for the server you are using so that you know how long your data will be kept. 

- If you use more than one Galaxy server (e.g. Galaxy-Mel and useGalaxy.org) you need to register and log in separately for each server. They don't talk to each other. 

## Tutorials

Go to Galaxy-Mel and log in, then try these tutorials:

* [Introduction to Galaxy](../tutorials/galaxy_101/galaxy_101.md) 
* [Galaxy Workflows](../tutorials/galaxy-worklows/galaxy-workflows) 
* Other MB tutorials, e.g. Assembly, RNA-seq, etc. 

## Galaxy Training Network

The Galaxy Training Network hosts a large collection of useful training material [here](http://galaxyproject.github.io/training-material/).

To get started, go to [https://usegalaxy.org/](https://usegalaxy.org/), log in, then try these tutorials: 

* [Introduction to Galaxy](http://galaxyproject.github.io/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html)
* [Galaxy histories](http://galaxyproject.github.io/training-material/topics/introduction/tutorials/galaxy-intro-history/tutorial.html)

[![GTN logo](media/GTN_logo.png)](https://galaxyproject.org/teach/gtn/)


## Running your own Galaxy server in the cloud

It is possible to run your own Galaxy instance using the Nectar cloud. 

- [Tutorial to launch your own Galaxy](../tutorials/gvl_launch/gvl_launch.md)

- [Nectar: https://nectar.org.au](https://nectar.org.au/about/)

## Running Galaxy locally using Docker

It is usually preferable to use a docker Galaxy image rather than installing Galaxy itself locally, for tool depencies. 

- The docker container is at [https://hub.docker.com/r/bgruening/galaxy-stable/](https://hub.docker.com/r/bgruening/galaxy-stable/)

- [Docker tutorial link](../tutorials/docker/docker.md)

- Run with `docker run -p 80:80 bgruening/galaxy-stable`
- In a web browser, enter "localhost" in the address bar
- Your Galaxy should now be running. 



















