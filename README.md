# docker_flask_homework
docker homework

## Part 1

See the Dockerfile for all the steps in creating the docker app

This screenshot shows the created dockerized flask app running on the 5001 port
![Screen Shot 2023-12-03 at 14 06 47](https://github.com/chebbin/docker_flask_homework/assets/141374142/6736bfcb-d744-45fa-912e-bbfb800d5960)

This screenshot shows the shell environment with the dockerfile, docker image and container ID
![Screen Shot 2023-12-03 at 14 09 45](https://github.com/chebbin/docker_flask_homework/assets/141374142/b2db85f6-0979-4cfd-b07b-ab8d0b81dcda)

## Part 2

1. Create two flask apps and dockerfiles for each
2. Create a yaml file
3. Use the following command the create the docker app: docker-compose up --build

What are some differences between Docker and Docker-compose?
1. Docker run can only start one container at a time, while Docker-compose allows you to configure and run multiple docker containers at once.
2. Docker run is command line based, while docker compose reads the configuration data from a YAML file
3. Docker Compose allows for ease of reflecting local changes in the containerized application. With Docker Compose, changes made locally are automatically mirrored in Docker without the need to rebuild the image. With Docker alone, rebuilding is necessary for changes to take effect.

The following screenshot shows that both flask apps are running
![Screen Shot 2023-12-03 at 18 46 40](https://github.com/chebbin/docker_flask_homework/assets/141374142/e7eecd3d-3079-452e-857a-afcc2733f115)

Screen shot of dockerapp1 running on port 5001
![Screen Shot 2023-12-03 at 18 49 38](https://github.com/chebbin/docker_flask_homework/assets/141374142/14a48012-7839-44a3-bad3-23ca54db1bfd)

Screen shot of dockerapp2 running on port 5002
![Screen Shot 2023-12-03 at 18 52 07](https://github.com/chebbin/docker_flask_homework/assets/141374142/209990ef-5497-4209-bbbc-1c10462c69ae)
