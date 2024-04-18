# Docker-GPU-activation
Follow the below link to download the nvidia driver
https://www.nvidia.com/download/index.aspx 

![Screenshot 2024-03-02 171942](https://github.com/oyasizaki/Docker-GPU-activation/assets/118342512/6b60b087-0ea0-42ea-bb0f-6ee0e2964d7b)


Open the command prompt (Recommended PowerShell Administrator)

```shell
wsl --install
```

* With this command it will install wsl and ask to restart your device 

* Now `Restart` your machine for Ubuntu to download and finishing the installation process 

* After this, check if tyhe gpu can be detected in the wsl 

```shell
nvidia-smi
```
![Screenshot 2024-03-02 175725](https://github.com/oyasizaki/Docker-GPU-activation/assets/118342512/653a60d6-8f4b-4f56-8c45-b92293eaaf95)

## Now Download the Docker Desktop from the link below
`https://www.docker.com/products/docker-desktop/`
![DD](https://github.com/oyasizaki/Docker-GPU-activation/assets/118342512/9d45ca86-62b6-4bcc-9c3c-74d50ae43bd7)

## Install 
Now click on the downloaded docker desktop file for installing the app.
