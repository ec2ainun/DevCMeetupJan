# Demo DevCMeetupJan

[Source](https://github.com/thtrieu/darkflow)

Real-time object detection and classification. Paper: [version 1](https://arxiv.org/pdf/1506.02640.pdf), [version 2](https://arxiv.org/pdf/1612.08242.pdf).

## Instalasi 
    ```
    pip3 install -e .
    ```

## Install Nvidia-docker
untuk support komputasi GPU 
```sh
   > wget https://gist.githubusercontent.com/ec2ainun/7ff1e0d964833a3177f7685deb0e47b0/raw/2f203519d949a660b549f41b7ce2c3c089164f0d/basic-GPU.sh
```

## Docker
masuk ke folder dl-docker, lalu build image:
```sh
   > docker build -t nama-image .
   #namaImage bisa anda ganti sesuai interest anda
```
atau pull image dan run container dari docker hub :
```sh
   >  nvidia-docker run -it -p 8888:8888 -p 6006:6006 -p 3000-3005:3000-3005 ec2ainun/dl-talks:stable
```