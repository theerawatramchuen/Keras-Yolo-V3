# keras-yolo3
## Original Source [bing0037](https://github.com/bing0037/keras-yolo3)
![](https://github.com/theerawatramchuen/Keras-Yolo-V3/blob/master/pictures/test_result.png)
### 1. Download the model [yolo.h5](https://drive.google.com/uc?export=download&confirm=8R0l&id=1Dd-uUhhXvosXiIIZM8tiXoZyENJxIY4u) to 'model_data/' directory directly
### 2. Go ahead test it with 'funny_dog.mp4' the result keep in folder 'test_data/' as below command line.
python yolo_cam.py
![](https://github.com/theerawatramchuen/Keras-Yolo-V3/blob/master/test_data/result_66.jpg)
### 3. Edit yolo_cam.py the last line for WebCam cv2.VideoCapture(0) input
detect_video(cam,'funny_dog.mp4','test_data/') ### for video file input

to

detect_video(cam,0,'test_data/') ### for Webcam input
