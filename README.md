# Human_detection_with_yolov8

1. Download Yolov8 source code form github
- Step 1:Acess the github link of yolov8 ([link](https://github.com/ultralytics/ultralytics))
  
  ![Image 1](Image/Image%201.png)

- Step 2: Choose Code and copy link
  ![Image 2](Image/Image%202.png)

- Step 3: git clone 
  ![Image 3](Image/Image%203.png)

2. Install the necessary Python library packages required by YOLOv8. The YOLOv8 source code is built using a variety of Python libraries. So, to be able to run YOLOv8, we need to download the libraries that YOLOv8 requires. YOLOv8 has built-in library called ultralytics, we can download this library via pip command as follows:
![Image 4](Image/Image%204.png)

3. Download pretrain model
![Image 5](Image/Image%205.png)

6. Prepare data
To train YOLOv8 on any set of data, we need two main components as follows:
- Directory containing data: You need to prepare a directory containing the data set (this directory is located in the YOLOv8 directory) with the following directory tree structure:
  ![Image 6](Image/Image%206.png)
- File .yaml: You need to prepare .yaml containing information about the above dataset in the data directory
![Image 7](Image/Image%207.png)

7. Training 
After completing the above preparation steps, we will perform training with the prepared data set
![Image 8](Image/Image%208.png)

1. VAlidating
![Image 9](Image/Image%209.png)

1. Predict 
![Image 10](Image/Image%2010.png)

1.  Result 
![Image 11](Image/Image%2011.jfif)