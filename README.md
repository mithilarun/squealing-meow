# squealing-meow
src for mithilarun.com

## Prerequisites
* Docker
* The nginx image for docker

## Installation
To create a docker image with this website, run the following:

    docker build -t squealing-meow-content .

Once the image is created, we need to start it:

    docker run --name squealing-meow -d -p 80:80 squealing-meow-content


## References
I have used twitter bootstrap to set this website up. You find the source
and documentation for twitter bootstrap here: http://getbootstrap.com
