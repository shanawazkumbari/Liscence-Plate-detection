# Liscence Plate Detection
This project is based upon object detection and as the names suggests we are going to detect liscence plate

Firstly I have collected images and drew bounding boxes with a tool called LabelBox which creates .xml for each image
The xml_to_csv.py code gathers all data from all xml files and creates a csv file which is used in Liscence Plate Detection.ipynb 

The Liscence Plate Detection.ipynb file contains the main python code where in all the pre processing and the model training is done. The model is then saved in json format.



