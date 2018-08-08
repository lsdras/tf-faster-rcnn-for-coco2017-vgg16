Modified for coco2017 dataset.

Oirginally written by https://github.com/endernewton/tf-faster-rcnn. If you want more reports, visit that site.

Procedures before training are all same as original
But, when you clone and install this one.

$./experiments/scripts/train_faster_rcnn.sh 0 coco vgg16

will read and train images in /data/coco/images/train2017 and validation and detection also.

when you want to detect your own picture by using weights trained by coco.
use demo.py.
demo.py is also fitted for coco detection process. But, you need to change the weight number and image name in the demo.py depend on your situation.


This repositoty will closed if there's any copywrite problem exist.