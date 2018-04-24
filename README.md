# CV_Datasets
Description of computer vision datasets.

## MNIST (http://yann.lecun.com/exdb/mnist/)
The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

* Handwriting digits from 0 to 9
* **60,000 training examples** [features](http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz) [labels](http://yann.lecun.com/exdb/mnist/train-labels-idx1-ubyte.gz)
* **10,000 test examples** [features](http://yann.lecun.com/exdb/mnist/t10k-images-idx3-ubyte.gz) [labels](http://yann.lecun.com/exdb/mnist/t10k-labels-idx1-ubyte.gz)
* Image classification

## Imagenet (http://image-net.org)
ImageNet is an image dataset organized according to the WordNet hierarchy. Each meaningful concept in WordNet, possibly described by multiple words or word phrases, is called a "synonym set" or "synset". There are more than 100,000 synsets in WordNet, majority of them are nouns (80,000+). In ImageNet, we aim to provide on average 1000 images to illustrate each synset. Images of each concept are quality-controlled and human-annotated. In its completion, we hope ImageNet will offer tens of millions of cleanly sorted images for most of the concepts in the WordNet hierarchy.

[Summary and Statistics](http://image-net.org/about-stats) (updated on April 30, 2010) 

* Total number of non-empty synsets: 21841
* **Total number of images: 14,197,122**
* Number of images with bounding box annotations: 1,034,908
* Number of synsets with SIFT features: **1000**
* Number of images with SIFT features: 1.2 million

## COCO (http://cocodataset.org)
COCO is a large-scale **object detection**, **segmentation**, and **captioning dataset**.

* Object segmentation
* Recognition in context
* Superpixel stuff segmentation
* **330K images (>200K labeled)**
* 1.5 million object instances
* **80 object categories**
* 91 stuff categories
* **5 captions per image**
* 250,000 people with keypoints
