# deeplearning
## 深度学习框架配置
## 所有配置教程本人全部亲自测试并且通过验证的
## [有道云笔记链接](http://note.youdao.com/noteshare?id=3a9cc8630338ed19528d69872e8fcdca&sub=177A57A52F7E427691496BE297B5BA33)


一、装系统  
+ 1.1 [ubuntu系统镜像链接](http://note.youdao.com/noteshare?id=8d2854f7afcef0f707eb488e15536239&sub=95DDAD1F5E044C3E8D070E87D001FA2B)   
+ 1.2 [刻录镜像盘](http://note.youdao.com/noteshare?id=345f6cb56f5e5070aeaeecde6145f94b&sub=0E01296BC8734890AFB4DEF0B5AEB3E8)   
+ 1.3 [做ubuntu系统](http://note.youdao.com/noteshare?id=3545e0cfde5ea4b58ddc3d999ca32911&sub=0223DFF8B1FB4E46BFE565F2D743FFED)  

二、[nvidia显卡驱动安装](http://note.youdao.com/noteshare?id=b19435701f4e6a5133f7e6d0425f3705&sub=FAD9B32FA17347B899CE8DA4A65C77D8)  

三、[cuda和cudnn安装](http://note.youdao.com/noteshare?id=37733a47511ed1ef5ad57f16f5b59bca&sub=08FF78F413F643EF88C55CE98CED84FA)  

四、[anaconda安装](http://note.youdao.com/noteshare?id=ac5489887fdb5a289238ab135c93048a&sub=4D79E2D7EAA64B7D93FD9D8FF00C5064)  

五、[tensorflow和keras安装](http://note.youdao.com/noteshare?id=efabd685c2add61a38750ec1a812dcd9&sub=2EB753EDE7BA4E94AF70DE46563D689F)  

六、[pytorch安装](http://note.youdao.com/noteshare?id=3e2e734e26ecd1e0c763505c312eaed5&sub=27DBBD2A18594353992ABFAB2BDEDE61)  

七、[ubuntu c++版本opencv安装](http://note.youdao.com/noteshare?id=2f57e026127393d7fc078a6cb1b9598b&sub=ABB136F8F05C43D78391F83BECF4DB94)  

八、[YOLO安装](http://note.youdao.com/noteshare?id=49c34adb21a6f281469bfcc3d3ee82b3&sub=1367D6970A6446C29FF8DFD7E7C2EE32) 

九、[虚拟环境--版本号管理(待续...)]()


其他资料：
+ [学习资料](http://note.youdao.com/noteshare?id=e4598e03330c2c26c6fe713b6b792ce2&sub=1317688C484543918E281FD758A0751D)
+ [论文查找和下载](http://note.youdao.com/noteshare?id=713f336aea3736f5b9a3175395c0468a&sub=ECD7BE79AED640FC863D2EC43A3A35C2)
+ [参考文献方法](http://note.youdao.com/noteshare?id=d2ca2afdc50b97cd5d10ce7ad44bf141&sub=7A4E0024B0BD45359227318AE7060E1C)
+ [arxiv论文怎么读](http://note.youdao.com/noteshare?id=42a06ee91e679d750ffc3dc049d3751e&sub=4A727CDDA3FF4F50B748FE6D3DDA0548)

+ [pip和conda换国内源](http://note.youdao.com/noteshare?id=f7daffbb051dfe0dd0944f8abdef5f6b&sub=83D349B121874BBAA7EB519D7B9C48BC)
+ [解决：Ubuntu16.04循环登录和重新安装显卡驱动](http://note.youdao.com/noteshare?id=26b3fd8d702ad1e72c96381386fcf500&sub=4445DD8709504B7497833860970818E4)
+ [虚拟机安装linux系统界面显示不全解决办法](http://note.youdao.com/noteshare?id=0d08fde70b892d3b6c3be77d491f9b26&sub=9C957CE5F2264F1CA9B0897252285B09)
+ [查看python包路径和版本号](http://note.youdao.com/noteshare?id=2d91e786aa91c30b9c955dbf8067943f&sub=86D2887F3F964A418CFD0EBD7E7E4203)
+ [windows+ubuntu双系统](http://note.youdao.com/noteshare?id=d9828f20c1c601a065a82d5dc6adbd3c&sub=9B9C645AD4324B559C89CC21443C3D64)
+ [pip和anaconda下载安装源地址--离线安装包](http://note.youdao.com/noteshare?id=c0f25de846da8ef84ab01c452506fdee&sub=E63B786E288B49B084C5A4B597F501BC)
----
深度学习框架版本简单查看方法
```
bubble@bubble:~$ python
Python 3.6.5 |Anaconda, Inc.| (default, Apr 29 2018, 16:14:56) 
[GCC 7.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorflow
/home/bubble/anaconda3/lib/python3.6/site-packages/h5py/__init__.py:36: FutureWarning: Conversion of the second argument of issubdtype from `float` to `np.floating` is deprecated. In future, it will be treated as `np.float64 == np.dtype(float).type`.
  from ._conv import register_converters as _register_converters
>>> tensorflow.__version__
'1.13.1'
>>> import keras
Using TensorFlow backend.
>>> keras.__version__
'2.2.4'
>>> import torch
>>> torch.__version__
'1.1.0'
>>> import cv2
>>> cv2.__version__
'3.3.0'
>>>
```
