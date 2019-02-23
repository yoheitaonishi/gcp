# gcp

## create bucket at storage

bucket is reginal and place is northen america
after that, add data files in `input` directory

## create vm instance at computer engine

vCPU x 8, Ubuntu 16.04 LTS and set public key for ssh access

## install gcp's ubuntu

```
sudo apt update
sudo apt install git vim build-essential tmux htop
```

go to anaconda website and copy linux download address.
```
wget [anaconda download address]
sh [anaconda sh file]
source .bashrc
```

## github

create secret github repo and clone from gcp command line

## data transfer

```
mkdir input
gsutil -m cp -r gs://[bucket name]/input/* input/
```

## Decompressed data

```
sudo apt-get install zip unzip
unzip [file name]
```



