🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU

### Template
https://runpod.io/gsc?template=fvddsynfnn&ref=iqi9iy8y

### Tutorial Video
https://www.youtube.com/watch?v=STecUG4RBxM

### Jupyter Lab Notebook

```py
!apt update && apt install -y libgl1
%cd /content
!git clone https://github.com/jellyjamin/stable-diffusion-webui-colab
```

https://github.com/camenduru/stable-diffusion-webui-colab

### How to install

go to content folder

open new python notebook 

use above command

click on the version you want 

remove 
```py
%env TF_CPP_MIN_LOG_LEVEL=1

!apt -y update -qq
!wget http://launchpadlibrarian.net/367274644/libgoogle-perftools-dev_2.5-2.2ubuntu3_amd64.deb
!wget https://launchpad.net/ubuntu/+source/google-perftools/2.5-2.2ubuntu3/+build/14795286/+files/google-perftools_2.5-2.2ubuntu3_all.deb
!wget https://launchpad.net/ubuntu/+source/google-perftools/2.5-2.2ubuntu3/+build/14795286/+files/libtcmalloc-minimal4_2.5-2.2ubuntu3_amd64.deb
!wget https://launchpad.net/ubuntu/+source/google-perftools/2.5-2.2ubuntu3/+build/14795286/+files/libgoogle-perftools4_2.5-2.2ubuntu3_amd64.deb
!apt install -qq libunwind8-dev
!dpkg -i *.deb
%env LD_PRELOAD=libtcmalloc.so
!rm *.deb
```

### then run
