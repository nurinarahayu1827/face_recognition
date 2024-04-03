# Real Time Face Recognition System With Use Of Mask Occlusion
Making real time face recognition system using the faster R-CNN method to recognize people with and without mask occlusion.

Installation:
1. Install Anaconda Python
2. Open Anaconda Prompt
3. Create virtual environment with name "face_recognition"
4. Run "conda activate face_recognition"
5. Update & install dependencies "python -m pip install --upgrade pip"
6. Add it to Jupyter Kernel "python -m ipykernel install --user --name=face_recognition
7. Install Visual C++ Build Tools
8. Install Appropriate CUDA and cuDNN version based on python version (see https://www.tensorflow.org/install/source for more details) (in this project using Python 3.9.12)
9. Install Tensorflow
10. Download Tensorflow Model Garden (faster_rcnn_resnet50_v1_640x640_coco17_tpu-8)
(See what libraries or modules that have been used for this project in packages.txt)

For annotating face area:
1. Run "Making Annotation.ipynb" file in Colab
2. After annotating face area have been finished, save all images and it's XML files and check precision between the images and it's bounding box in Roboflow. Save it as tfrecord format.

Running Program:
1. Open Anaconda Prompt
2. Run "conda activate face_recognition" in folder path
3. Run "jupyter notebook"
4. Open and run "Training and Detection.ipynb"

Dataset:
https://universe.roboflow.com/ta-nqdaw/face_person_detection

