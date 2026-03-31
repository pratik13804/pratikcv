# **Object Detection using YOLOv5**

**Author:** Pratik Pandey

**Project:** L1 \- 03

*(Src: [The AI Technology](https://www.google.com/search?q=https://medium.com/the-ai-technology/segmentation-vs-object-detection-vs-classification-things-you-need-to-know-b86b05f5167b))*

## **1\. Overall Project Description**

Welcome to my hands-on tutorial for computer vision\! The primary goal of this repository is to demonstrate how to implement real-time 2D/3D object detection using deep learning.

This project utilizes the popular **YOLO (You Only Look Once)** architecture—specifically YOLOv5 by Ultralytics—to identify, classify, and draw bounding boxes around multiple objects within images and video streams. It acts as an introductory guide for computer vision enthusiasts or students.

## **2\. Tech Stack Requirements**

To run the code in this project, the following tools and libraries are required:

* **Python**  
* **PyTorch:** The deep learning framework that YOLOv5 is built on.  
* **OpenCV:** For handling and rendering video/image processing.  
* **Google Colab:** The recommended execution environment (highly accessible as it doesn't require a local GPU).  
* **YOLOv5 Repository:** We will clone this directly from the Ultralytics GitHub.

## **3\. Workflow & Implementation Steps**

The core executable code is located in the Object\_Detection\_with\_YOLOv5.ipynb notebook. The workflow is broken down into the following steps:

1. **Preparation:** Open the provided notebook in Google Colab.  
2. **Installation:** Run the initial cells to clone the official YOLOv5 repository and install all required Python dependencies (via requirements.txt).  
3. **Model Loading:** Load a pre-trained PyTorch model (e.g., yolov5s.pt) into memory.  
4. **Image Inference:** Perform object detection on static images.  
5. **Video Inference:** Provide a video path, let the model process the media frame-by-frame, and utilize OpenCV (cv2.VideoCapture, cv2.imshow) to display or save the annotated output showing the detected objects.

## **4\. Contributing**

If you want to contribute to this project, you are heavily encouraged to do so\! You can either add new detection models, improve existing pipelines, or fix bugs.

Please follow these steps to contribute:

1. Fork this repository and clone it to your local machine.  
2. Create a new branch with a descriptive name for your contribution.  
3. Add your code/files to the branch and commit your changes.  
4. Push your branch to your forked repository and create a pull request to the main repository.  
5. Wait for your pull request to be reviewed and merged.

## **5\. References**

* [YOLOv3 \- Ultralytics](https://github.com/ultralytics/yolov3)  
* [YOLOv5 \- Ultralytics](https://github.com/ultralytics/yolov5)

*Maintained by Pratik Pandey*