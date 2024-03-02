# Docker-GPU-activation
Follow the below link to download the nvidia driver
https://www.nvidia.com/download/index.aspx 

![Screenshot 2024-03-02 171942](https://github.com/oyasizaki/Docker-GPU-activation/assets/118342512/6b60b087-0ea0-42ea-bb0f-6ee0e2964d7b)


Open the command prompt (Recommended PowerShell Administrator)

```shell
wsl --install
```

With this command it will install Ubuntu 

After this check if tyhe gpu can be detected in the wsl 

```shell
nvidia-smi
```
