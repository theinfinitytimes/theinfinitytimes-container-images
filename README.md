# theinfinitytimes-container-images
This repository has the necessary compose files to get the 
theinfinitytimes webpage up and running

In the compose file, we create a network with 3 containers
*  one for the api,
*  one for the frontend
*  one for the database
with the following images from the dockerhub
*  theinfinitytimes/theinfinitytimes-api
*  theinfinitytimes/theinfinitytimes
*  mongo

## Instructions
To get this up and running 
*  Clone the repository 
    ```console
    git clone git@github.com:theinfinitytimes/theinfinitytimes-container-images
    ```
*  From the repository's directory run
    ```console
    docker-compose up
    ```

