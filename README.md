# SqueezeNet for the ncnn framework
Papers <br/>
https://arxiv.org/pdf/1602.07360.pdf <br/>
Training set: ImageNet 2012 <br/>
Size: 227x227 <br/>
Prediction time: 85 mSec (RPi 4) <br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/opencv-c-examples-on-raspberry-pi.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/SqueezeNet-ncnn/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
cat.jpg <br/>
hippo.jpg <br/>
shufflenet.bin <br/>
shufflenet.param <br/>
ShuffleNet.cpb <br/>
shufflenetv2.cpp <br/>
 <br/>
Run ShuffleNet.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>

![output image]( https://qengineering.eu/images/SqueezeNet_Hippo.jpg )

