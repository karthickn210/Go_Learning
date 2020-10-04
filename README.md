# Go_Learning
This Repo contains my learning of this language and hope it helps if you want to learn the same.

## Intro
Go is a open source programming language that makes it easy to build simple, reliable, and efficient software.Now a days it getting more popular

## My System details
| Software        | Version   |
|-----------------|-----------|
| Ubuntu 64 bit   | 20.04 LTS |
| Go              | 1.15.2    |

## Installation
Installation Steps for linux

1. If you think you may have previous version of golang install, or you’re not sure, run the following commands to completely remove of any trace of golang on your system.
  ~~~
  sudo apt remove golang
  sudo apt autoremove
  ~~~
2. Go to the official website of GO and download the latest software. [click here for download page](https://golang.org/dl/)
    __Note__: Don't use apt command to install it, I won't recommend this because it won't be latest version and it install the package in weird location.    
3. Next `cd` into the download folder and extract it using the below command or using `GUI` itself extract it
  ~~~
  cd /Download
  sudo tar -xvf go1.15.2.linux-amd64.tar.gz
  ~~~  
4. Now we need to move the extracted files into recommended location by the official golang docs, which is `/usr/local` to do this follow the below command
  ~~~
  sudo mv go /usr/local
  ~~~
5. Then we have the go language and compiler in the correct location we just need to be able to access it through our terminal. For that we have to tell the system about golang by adding it to the global PATH with help of the below command,
  ~~~
  sudo echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.bashrc
  ~~~
6. Now restart the terminal and enter the command `go version` now it will shows the version that you installed like below,
  ~~~
  go version go1.15.2 linux/amd64
  ~~~
  
Now you successfully installed go language in your machine

##### happy coding!!
