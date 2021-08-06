Object-Detection using Yolov3(pretrained model) 

In Yolo V3 a single neural network is applied to the entire image, dividing the image into 
regions and predicting the bounding boxes and probabilities for each region. The bounding 
boxes are weighed by predicted probabilities, the most suitable bounding box can be 
determined using non max suppression(nms).

In prior algorithms the model was applied to an image at multiple locations and scales, the high scoring regions are considered as object detected(R-CNN require about 
1000 networks for a single image).

=> yolov3 much faster and efficient.

paper:https://pjreddie.com/media/files/papers/YOLOv3.pdf

https://github.com/pjreddie/darknet/blob/master/data/coco.names

pretrained weights and cfg files can be downloaded: https://pjreddie.com/darknet/yolo/
