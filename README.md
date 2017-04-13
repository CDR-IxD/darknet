
#Peter's Version of Video Object Recognition

1. Clone the repo into your local drive
2. Download yolo.weights from pjreddie site 
```
wget http://pjreddie.com/media/files/yolo.weights
```
3. Get the video that you want to analysize (ideally down-size it if you want to do it quickly)
4. run the following code
```
./darknet detector demo cfg/coco.data cfg/yolo.cfg yolo.weights "YOUR_VIDEO_FILE_HERE"
```
5. The output text file should be in the root of darknet with th ename Output_YOUR_VIDEO_FILE_HERE.txt as the name. 

_______________________________________________________________________________
![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

# CDR Fork of YOLO used for video analysis:
Edited by Peter Wang

## instructions for Usage
1. Clone the repo to your directory
2. Download yolo.weights and place into darknet/ directory
3. Edit makefile options to make sure that you are ready to go 
