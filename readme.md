# Overview

This is a sandbox repo for various experiments with face detection, recognition, and object detection. 

## Notes

### Related work

* Video of face generation with sketches: https://www.instagram.com/p/BUU8TuQD6_v/


### Helpful

* Optimizing python and opencv: https://www.pyimagesearch.com/2015/12/21/increasing-webcam-fps-with-python-and-opencv/
* Google object detection example: https://towardsdatascience.com/building-a-real-time-object-recognition-app-with-tensorflow-and-opencv-b7a2b4ebdc32
* Download binaries of tensorflow for Mac; 30-40% speed increase: https://github.com/lakshayg/tensorflow-build
* face_recognition library's demo code: https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_from_webcam_faster.py
* head pose estimation: https://www.learnopencv.com/head-pose-estimation-using-opencv-and-dlib/

### Download pretrained models

MODEL_NAME = 'ssd_mobilenet_v1_coco_2017_11_17'
MODEL_FILE = MODEL_NAME + '.tar.gz'
DOWNLOAD_BASE = 'http://download.tensorflow.org/models/object_detection/'

# Path to frozen detection graph. This is the actual model that is used for the object detection.
PATH_TO_CKPT = MODEL_NAME + '/frozen_inference_graph.pb'

# List of the strings that is used to add correct label for each box.
PATH_TO_LABELS = os.path.join('data', 'mscoco_label_map.pbtxt')

http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v1_coco_2017_11_17.tar.gz
http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v1_coco_2017_11_17/data/mscoco_label_map.pbtxt

