# Tech_Geek
Yolo Model BOSCH AI Hackathon


This model uses the following file:
 
 1.  yolov4.conv.137 to be placed under darknet-alexeyAB-master folder
 2.  yolov4-obj.cfg to be placed under cfg folder
 3.  obj.names to be placed under data folder
 4.  obj.data to be placed under data folder
 5.  yolov4-obj_8000.weights under darknet-alexeyAB-master folder


To run prediction:
On Linux use ./darknet  as given below:
./darknet detector test data/obj.data cfg/yolov4-obj.cfg yolov4-obj_8000.weights -ext_output test_image.jpg > result.txt

on windows use darknet.exe as given below:
darknet.exe detector test data/obj.data cfg/yolov4-obj.cfg yolov4-obj_8000.weights -ext_output test_image.jpg > result.txt

On Linux find executable file ./darknet in the root directory, while on Windows find it in the directory \build\darknet\x64


To know more about compilation steps, kindly refer to the below link:
https://github.com/artynet/darknet-alexeyAB
