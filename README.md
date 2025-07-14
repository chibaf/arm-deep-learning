# arm-deep-learning

## References
Install ARMnn on Raspberry Pi 4 - Q-engineering
https://qengineering.eu/install-armnn-on-raspberry-pi-4.html

The ARM holding, producer of the ARM chips found in most smartphones and Raspberries, has developed a framework for these devices. They call it the ARMnn. Recently the holding donated the software to Linaro, where it is now open source. This framework is capable of running TensorFlow, TensorFlow Lite, Caffe or ONNX models without any converter tool. It makes interfacing easy.

However, there are some issues with this framework. It requires a lot of additional software, including full installation of TensorFlow. In the end, ARMnn occupies 3.1 Gbyte on your SD card. The software documentation is not very thorough. For instance, where to connect inputs and outputs to the tensors is not very clear. And the framework is very slow, seven times slower than TensorFlow Lite in the same conditions. For those interested, the installation procedure and software examples can are here.
