### Docker Commands

- docker images - view which images have been pulled to local system
EX. 
root@ubu:/var/lib/docker# docker images
REPOSITORY              TAG       IMAGE ID       CREATED       SIZE
45drives/zfs_exporter   v2.2.5    0e195c658f6d   2 years ago   1.11GB

- docker inspect <namespace>/<repository>:<tag> -
EX.
docker inspect 45drives/zfs_exporter:v2.2.5




### Docker Reference

- Image Name Structure - <registry>/<namespace>/<repository>:<tag>
EX. 
docker pull 45drives/zfs_exporter:v2.2.5
Note: The registry is docker.io