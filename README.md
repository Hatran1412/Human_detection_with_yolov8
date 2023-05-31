# Human_detection_with_yolov8

1. Download Yolov8 source code form github
- Step 1:Acess the github link of yolov8 ([link](https://github.com/ultralytics/ultralytics))
  
(Image\Image 1.png)

- Step 2: Choose Code and copy link
  (Image\Image 2.png)

- Step 3: git clone 
  (Image\Image 3.png)

2. Install the necessary Python library packages required by YOLOv8. The YOLOv8 source code is built using a variety of Python libraries. So, to be able to run YOLOv8, we need to download the libraries that YOLOv8 requires. YOLOv8 has built-in library called ultralytics, we can download this library via pip command as follows:
(Image\Image 4.png)

3. Download pretrain model
(Image\Image 5.png)

4. Prepare data
To train YOLOv8 on any set of data, we need two main components as follows:
- Directory containing data: You need to prepare a directory containing the data set (this directory is located in the YOLOv8 directory) with the following directory tree structure:
  (Image\Image 6.png)
- File .yaml: You need to prepare .yaml containing information about the above dataset in the data directory
(Image\Image 7.png)

5. Training 
After completing the above preparation steps, we will perform training with the prepared data set
(Image\Image 8.png)

6. VAlidating
(Image\Image 9.png)

7. Predict 
(Image\Image 10.png)

8. Result 
(Image\Image 11.png)