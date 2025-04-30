# data-transfer
How to get the data you need for your research to and from high-performance computing systems.

## Tutorial 1: Downloading data from the internet

The aim of this tutorial is to introduce you to command-line tools that are useful for downloading data from the internet to your personal computer or an HPC system, and verifing the data is correct. There are two datasets we'll be working with as part of these exercies. 

- The [CIFAR-10](https://en.wikipedia.org/wiki/CIFAR-10) dataset is a collection of images that are commonly used to train machine learning and computer vision algorithms. It contains 60K 32x32 color images in 10 different classes. The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. There are 6K images of each class.
- [ImageNet](https://www.image-net.org) is an image database organized according to the [WordNet](https://wordnet.princeton.edu) hierarchy, in which each node of the hierarchy is depicted by hundreds and thousands of images. It currently consissts of more than than 14M images across 20K categories that have been hand-annotated by the project to indicate what objects are pictured and in at least one million of the images, bounding boxes are also provided. The most popular subset of images is the Imagenet-1K ([ILSVRC2012](https://en.wikipedia.org/wiki/ImageNet#History_of_the_ImageNet_challenge)) dataset, which spans 1K classes, 1.2M training images, 50K validation images, and 100K test images.

### Exercise 0: Login to Expanse via SSH

Let's get started by logging into Expanse with your training account either via the Expanse User Portal or directly via SSH from your terminal application.

*Command:*
```
ssh etrain75@login.expanse.sdsc.edu
```

*Output:*
```
mkandes@hardtack:~$ ssh etrain75@login.expanse.sdsc.edu
(etrain75@login.expanse.sdsc.edu) Password:
Welcome to Bright release         9.0

                                                         Based on Rocky Linux 8
                                                                    ID: #000002

--------------------------------------------------------------------------------

                                 WELCOME TO
                  _______  __ ____  ___    _   _______ ______
                 / ____/ |/ // __ \/   |  / | / / ___// ____/
                / __/  |   // /_/ / /| | /  |/ /\__ \/ __/
               / /___ /   |/ ____/ ___ |/ /|  /___/ / /___
              /_____//_/|_/_/   /_/  |_/_/ |_//____/_____/

--------------------------------------------------------------------------------

Use the following commands to adjust your environment:

'module avail'            - show available modules
'module add <module>'     - adds a module to your environment for this session
'module initadd <module>' - configure module to be loaded at every login

-------------------------------------------------------------------------------
Last login: Tue Apr 29 09:09:07 2025 from 208.58.212.11
[etrain75@login02 ~]$
```

### Exercise 1: wget - non-interactive network downloader

[wget](https://en.wikipedia.org/wiki/Wget) is a simple command-line tool for downloading files from the web. It supports [HTTP/S](https://en.wikipedia.org/wiki/HTTPS) and [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) protocols as well as file retrieval through [proxy servers](https://en.wikipedia.org/wiki/Proxy_server). It has been designed for robustness over slow or unstable network connections. If a download fails due to a network problem, you can setup the download to keep retrying, resuming the download from where you left off until the whole file has been retrieved.

#### Download a file

*Command:*
```
wget https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz
```

*Output:*
```
[etrain75@login02 ~]$ wget https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz
--2025-04-30 06:48:30--  https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz
Resolving www.cs.toronto.edu (www.cs.toronto.edu)... 128.100.3.30
Connecting to www.cs.toronto.edu (www.cs.toronto.edu)|128.100.3.30|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 170498071 (163M) [application/x-gzip]
Saving to: ‘cifar-10-python.tar.gz’

cifar-10-python.tar 100%[===================>] 162.60M  36.9MB/s    in 4.9s    

2025-04-30 06:48:47 (32.9 MB/s) - ‘cifar-10-python.tar.gz’ saved [170498071/170498071]

[etrain75@login02 ~]$
```

## Exercise X: Data Transfer Tools



# About COMPLECS

COMPLECS (COMPrehensive Learning for end-users to Effectively utilize
CyberinfraStructure) is a new [SDSC](https://www.sdsc.edu) program where 
training will cover non-programming skills needed to effectively use 
supercomputers. Topics include parallel computing concepts, Linux tools and
bash scripting, security, batch computing, how to get help, data management
and interactive computing. COMPLECS is supported by 
[NSF award 2320934](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2320934).

<img src="./images/NSF_Official_logo_Med_Res_600ppi.png" alt="drawing" width="150"/>
