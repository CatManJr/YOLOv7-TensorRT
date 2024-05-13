This is a application aiming to deploy an python trained model (.onnx file) to Windows (later than Windows10) platform.

The pre-trained model is compile and can be call by using Cuda C++, and with OpenCV library, a console application that using the .trt model to reason any images, videos & even cameras is developed.

Acknowledgements to the open source original model from https://github.com/WongKinYiu/yolov7,

and the guidance from Mr. Han Feiyu. http://github.com/FeiYull/TensorRT-Alpha

The application performed well on my machine, Windows 11, OpenCV 4.8.0, cuda 12.4, cuDNN 8.9.7.29, TensorRT 8.6.1.6, Visual Studio Community 2022. **Please check your cuDNN version. ONLY cuDNN 8.X is acceptable to TensorRT 8.X in this task.**

conda environment should strictly follow requirement.txt. 