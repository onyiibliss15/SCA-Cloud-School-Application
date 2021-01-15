# SCA CLOUD APPLICATION ASSESMENT

## DESCRIPTION
    Simple single page web site hosted on docker container

## REQUIREMENTS
    docker, click [here](https://docs.docker.com/engine/install/) to install
    docker-compose, click [here](https://docs.docker.com/compose/install/) to install. (only required if building from source)

## INSTALLATION
### From docker hub
[Link](https://hub.docker.com/r/onyinyebliss/sca_cloud_school_application) to docker hub repo: https://hub.docker.com/r/onyinyebliss/sca_cloud_school_application

    - pull image from hub
        `docker pull onyinyebliss/sca_cloud_school_application`
    - run container
        `docker run -it -d -p 8080:80 onyinyebliss/sca_cloud_school_application`
    - test
        `curl localhost:8080`
    - output 
        `<html>
            <h1>
                Welcome to SCA Cloud School Application, this is my first assesment.
            </h1>
        </html>`
