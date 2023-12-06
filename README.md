# Space Missions Kubernetes

Developing a Kubernetes version of this repo: https://github.com/danpg94/space_missions

to create Docker image, run:
```sudo docker build --build-arg ALLOWED_HOST_PARAM="{{vm_ip_address}}" . -t "{{vm_docker_route}}"```
```sudo docker run --detach -p 8080:80 space-missions-local```