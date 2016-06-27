# Install Caffe on Jetson TX1

Scripts to install Caffe and dependencies on the NVIDIA Jetson TX1 Development
Kit. Also installs some dependencies for Faster-RCNN.

To install, run the installCaffe.sh script
$ ./installCaffe.sh

To install with the cuDNN support, run the installCaffeCuDNN.sh script
$ ./installCaffeCuDNN.sh

To maximize the performance of the Jetson TX1, you can use the maxPerformance.sh
script which enables all CPU cores, and maximizes clock speeds on the CPUs and
GPU.
