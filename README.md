# data-transfer
How to get the data you need for your research to and from high-performance computing systems.

## Exercise 1: Downloading data from the internet

- [CIFAR datasets](https://www.cs.toronto.edu/~kriz/cifar.html) are labeled subsets of the 80 million tiny images dataset. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
-   

### wget - non-interactive network downloader

[wget](https://en.wikipedia.org/wiki/Wget) is a simple command-line tool for downloading files from the Web. It supports [HTTP/S](https://en.wikipedia.org/wiki/HTTPS) and [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) protocols as well as file retrieval through [proxy servers](https://en.wikipedia.org/wiki/Proxy_server). It has been designed for robustness over slow or unstable network connections. If a download fails due to a network problem, you can setup the download to keep retrying, resuming the download from where you left off until the whole file has been retrieved.

#### Download a file
```
wget https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz
```

# About COMPLECS

COMPLECS (COMPrehensive Learning for end-users to Effectively utilize
CyberinfraStructure) is a new [SDSC](https://www.sdsc.edu) program where 
training will cover non-programming skills needed to effectively use 
supercomputers. Topics include parallel computing concepts, Linux tools and
bash scripting, security, batch computing, how to get help, data management
and interactive computing. COMPLECS is supported by 
[NSF award 2320934](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2320934).

<img src="./images/NSF_Official_logo_Med_Res_600ppi.png" alt="drawing" width="150"/>
