# facial_recognition_pi

This is an end to end face recognition project for raspberry pi.

To run the programme follow the steps:

1.) Run 01_face_datasets.py script to add your face images. You have to tell your user id which will name the images according to that (Every Person will have there unique Id). Also create a folder dataset before running the script.

2.) Create a folder named trainer and then run 02_face_training.py which will create a yml trainer file in that folder. 

3.) In 03_face_recognition script add your name in list at a position according to your user Id. If you have user Id 1 the add your name in the first position of list. Finally RUn the script.

Modules used:

1.) OpenCV and OpenCV-contrib
2.) Pillow
3.) Numpy

Follow this amazing tutorial for installing opencv for Raspberry pi:
</https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/>
