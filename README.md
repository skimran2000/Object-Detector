#  Object Detector


This repository contains the code and resources to implemented an object detector which identifies the classes of the objects in an image or video.
- **Model Used** - pre-trained MobileNet-SSD v3 model

You need to download the weights and config file for the MobileNet-SSD v3 Model 
- **Weights file** - http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v3_large_coco_2020_01_14.tar.gz
The above file contains 'frozen_inference_graph.pb' which is needed.

- **Config file** - https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7/archive/2a20064a9d33b893dd95d2567da126d0ecd03e85.zip
The above file contains 'ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt' which is needed