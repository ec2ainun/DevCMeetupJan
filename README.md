# DevCMeetupJan

[Source](https://github.com/thtrieu/darkflow)
Real-time object detection and classification. Paper: [version 1](https://arxiv.org/pdf/1506.02640.pdf), [version 2](https://arxiv.org/pdf/1612.08242.pdf).

## Instalasi 
    ```
    pip install -e .
    ```
    
## Docker
masuk ke folder dl-docker, lalu build image:
```sh
   > docker build -t nama-image .
   #namaImage bisa anda ganti sesuai interest anda
```

atau pull image dari docker hub :
```sh
   >  nvidia-docker run -it -p 8888:8888 -p 6006:6006 ec2ainun/dl-talks:stable
```