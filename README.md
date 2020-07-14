## Requirements
Follow the link below to:
1: Install the Edge TPU runtime
2: Install the TensorFlow Lite library

https://coral.ai/docs/accelerator/get-started/#1a-on-linux



## Video Detection Inference 
python video_detection.py --model models/ssd_mobilenet_v2_coco_quant_postprocess_edgetpu.tflite --labels models/coco_labels.txt --video videos/cars.mp4
 --replace ssd_mobilenet_v2_coco_quant_postprocess_edgetpu.tflite with any other model name from models folder

## Image Detection Inference
python image_detection.py --model models/ssd_mobilenet_v2_coco_quant_postprocess_edgetpu.tflite --labels models/coco_labels.txt --image images/parrot.jpg
