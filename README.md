# docker-basic

In order to bult the image, and create the container from image and then run the container, go to the docker-local directory and use this command :
```
docker-basic
│───README.md
└───docker-local
    │───Dockerfile
    │───requirements.txt
    └───src
         │───server.py
```

- docker build -t hello-world-td . (to build the image)
- docker run hello-world-td (to create the container over an images specified and run the container)

## To check

- docker images (to see all the images built)
- docker images docker ps -a (to see all the container even after stopped running)
