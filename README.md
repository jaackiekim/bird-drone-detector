## Steps: 

Processing Dataset
To process the dataset, First of all, extract the images using the file extract_images.ipynb then split the dataset using split.ipynb

Training & Testing YOLOv7
After processing the dataset, using main_v7.ipynb to clone, train, and test YOLOv7 on the processed dataset.

Detect Drones Using YOLOv7
Once the YOLOv7 is trained, use the detect.py file from cloned yolov7 folder to detect the drones and use --save_text argument to save the bounding boxes in txt file.

Using Tracker
Use tracker_yolo_output.ipynb along with the video data and generated text file containing bounding boxes to get the CSRT Tracker Powered YOLOv7 Output
