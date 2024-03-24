This is a custom trained model which can recognize cars in an image (YOLOv5)

car.pt is the weight which is the output after training.
detect.py is program to detect objects.

I am also adding notebook for training custom models (YoloTrain.pynb)
In that inside yolo/data/coco128.yaml  modify it and make custom.yaml modify the paths in gcolab.
increase the epochs and execute and u will get your model last.pt.

in the detection change the weight and source they are yours....
