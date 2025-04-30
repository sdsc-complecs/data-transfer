# data-transfer
How to get the data you need for your research to and from high-performance computing systems.

## Exercise 1: Downloading data from the internet

- The [CIFAR-10](https://en.wikipedia.org/wiki/CIFAR-10) dataset is a collection of images that are commonly used to train machine learning and computer vision algorithms. It contains 60K 32x32 color images in 10 different classes. The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. There are 6K images of each class.
- [ImageNet](https://www.image-net.org) is an image database organized according to the [WordNet[(https://wordnet.princeton.edu) hierarchy, in which each node of the hierarchy is depicted by hundreds and thousands of images. It currently consissts of more than than 14M images across 20K categories that have been hand-annotated by the project to indicate what objects are pictured and in at least one million of the images, bounding boxes are also provided. The most popular subset of images is the Imagenet-1K ([ILSVRC2012](https://en.wikipedia.org/wiki/ImageNet#History_of_the_ImageNet_challenge)) dataset, which spans 1K classes, 1.2M training images, 50K validation images, and 100K test images. 

### wget - non-interactive network downloader

[wget](https://en.wikipedia.org/wiki/Wget) is a simple command-line tool for downloading files from the web. It supports [HTTP/S](https://en.wikipedia.org/wiki/HTTPS) and [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) protocols as well as file retrieval through [proxy servers](https://en.wikipedia.org/wiki/Proxy_server). It has been designed for robustness over slow or unstable network connections. If a download fails due to a network problem, you can setup the download to keep retrying, resuming the download from where you left off until the whole file has been retrieved.

#### Download a file
```
wget https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz
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
