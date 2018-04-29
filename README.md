# Description of computer vision datasets

## MNIST (http://yann.lecun.com/exdb/mnist/)
* The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

    * Handwriting digits from 0 to 9
    * **60,000 training examples** [features](http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz) [labels](http://yann.lecun.com/exdb/mnist/train-labels-idx1-ubyte.gz)
    * **10,000 test examples** [features](http://yann.lecun.com/exdb/mnist/t10k-images-idx3-ubyte.gz) [labels](http://yann.lecun.com/exdb/mnist/t10k-labels-idx1-ubyte.gz)
    * Image classification

## Imagenet (http://image-net.org)
* ImageNet is an image dataset organized according to the WordNet hierarchy. Each meaningful concept in WordNet, possibly described by multiple words or word phrases, is called a "synonym set" or "synset". There are more than 100,000 synsets in WordNet, majority of them are nouns (80,000+).

* [Summary and Statistics](http://image-net.org/about-stats) (updated on April 30, 2010) 

    * Total number of non-empty synsets: 21841
    * **Total number of images: 14,197,122**
    * Number of images with bounding box annotations: 1,034,908
    * Number of synsets with SIFT features: **1000**
    * Number of images with SIFT features: 1.2 million


* Challenages
    * [ILSVRC2017](http://image-net.org/challenges/LSVRC/2017/index) [results](http://image-net.org/challenges/LSVRC/2017/results)
        * Squeeze and Excitation Network ([webpage](https://shaoanlu.wordpress.com/2017/08/17/senet-winner-of-imagenet-2017/), [arXiv](https://arxiv.org/abs/1709.01507))
        * Dual Path Networks ([github](https://github.com/cypw/DPNs))
    * [ILSVRC2016](http://image-net.org/challenges/LSVRC/2016/index) [results](http://image-net.org/challenges/LSVRC/2016/results)
    * [ILSVRC2015](http://image-net.org/challenges/LSVRC/2015/index) [results](http://image-net.org/challenges/LSVRC/2015/results)
    * [ILSVRC2014](http://image-net.org/challenges/LSVRC/2014/index) [results](http://image-net.org/challenges/LSVRC/2014/results)
    * [ILSVRC2013](http://image-net.org/challenges/LSVRC/2013/index) [results](http://image-net.org/challenges/LSVRC/2013/results)
    * [ILSVRC2012](http://image-net.org/challenges/LSVRC/2012/index) [results](http://image-net.org/challenges/LSVRC/2012/results)
    * [ILSVRC2011](http://image-net.org/challenges/LSVRC/2011/index) [results](http://image-net.org/challenges/LSVRC/2011/results)
    * [ILSVRC2010](http://image-net.org/challenges/LSVRC/2010/index) [results](http://image-net.org/challenges/LSVRC/2010/results)

## COCO (http://cocodataset.org)
* COCO is a large-scale **object detection**, **segmentation**, and **captioning dataset**.

    * Object segmentation
    * Recognition in context
    * Superpixel stuff segmentation
    * **330K images (>200K labeled)**
    * 1.5 million object instances
    * **80 object categories**
    * 91 stuff categories
    * **5 captions per image**
    * 250,000 people with keypoints
    

* Challenages
    * [COCO2018](http://cocodataset.org/#detection-2018) **Detection task with object segmentation** `Ongoing`
        * Use the 2017 datasets for detection and keypoint
            *  Train images [118K/18GB](http://images.cocodataset.org/zips/train2017.zip)
            *  Validate images [5K/1GB](http://images.cocodataset.org/zips/val2017.zip)
            *  Test images [41K/6GB](http://images.cocodataset.org/zips/test2017.zip)
            *  Unlabeled images [123K/19GB](http://images.cocodataset.org/zips/unlabeled2017.zip)
        * [Cocoapi](https://github.com/cocodataset/cocoapi) for Lua, MATLAB, Python


## WebVision (https://www.vision.ee.ethz.ch/webvision/index.html)

* Designed to facilitate the research on learning visual representation from noisy web data.
* WebVision Dataset 2.0 (Over **5,000** synsets and **16 million** images images crawled from the Flickr website and Google Images search)

* Challenages
    * [WebVision Image Classification Task 2018](https://www.vision.ee.ethz.ch/webvision/challenge.html) `Ongoing`
