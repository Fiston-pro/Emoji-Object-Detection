# Live Object Detection with OpenVINO™

![office detection](./media/office.gif)
![road detection](./media/road.gif)

Object detection finds predefined objects in an image or video. Each returned object includes features such as label, probability and bounding box coordinates relative to image boundaries with an emoji on the right bottom corner. 

List of predefined objects available in this demo: person, bicycle, car, motorcycle, airplane, bus, train, truck, boat, traffic light, fire hydrant, stop sign, parking meter, bench, bird, cat, dog, horse, sheep, cow, elephant, bear, zebra, giraffe, backpack, umbrella, handbag, tie, suitcase, frisbee, skis, snowboard, sports ball, kite, baseball bat, baseball glove, skateboard, surfboard, tennis racket, bottle, wine glass, cup, fork, knife, spoon, bowl, banana, apple, sandwich, orange, broccoli, carrot, hot dog, pizza, donut, cake, chair, couch, potted plant, be, dining table, toilet, tv, laptop, mouse, remote, keyboard, cell phone, microwave, oven, toaster, sink, refrigerator, book, clock, vase, scissors, teddy bear, hair drier, toothbrush.

## Notebook Contents

This notebook demonstrates object detection with OpenVINO, using the [SSDLite MobileNetV2](https://github.com/openvinotoolkit/open_model_zoo/tree/master/models/public/ssdlite_mobilenet_v2) model from Open Model Zoo. The model was trained on [COCO dataset](https://cocodataset.org/#home).

## Installation Instructions

1. Start by making a virtual environment ```python3 -m venv venv```
2. Activate the virtual environment ```source venv/bin/activate```
3. Install the dependencies ```pip install -r requirements.txt```
4. Start your jupyter notebook ```jupyter notebook OpenVINO-object-detection.ipynb```

## Contribution

I still have alot of objects which are missing their emojis. To contribute on emojis: 
1. you can go on [Openmoji](https://openmoji.org/)
2. search for a missing object which is in the list of predefined objects but missing from emoji folder 
3. resize it to ```300X3000``` pixels
4. add it into emoji folder and name it, the respective name as shown in the list of predefined objects  
 