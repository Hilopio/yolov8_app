# yolov8_app
app for image detection with castom yolov8 model

### content
yolo_app.py - the application
yolo_m_50.onnx - the model in onnx format, used by the application
reqirements.txt - reqirements for using app
some examples from test dataset and internet:
    workers.jpg
    people.jpg
    test.jpg

### describtions
finds construction helmets and heads without helmets in the images

### execution:
python yolo_app.py %input_file% %output_file% (display)
input_file and output_file may be .jpg, .png, .bmp, ...
use keyword argument display to see the result

### for example:
python yolo_app.py workers.jpg output.jpg display
python yolo_app.py people.jpg output.jpg

### you may need to install:
    pip install onnx
    pip install onnxruntime
    pip install ultralytics

or just use reqirements.txt
