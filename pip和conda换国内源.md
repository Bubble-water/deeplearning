
# pip

## windows系统
只要新建一个配置文件，写上路径就行了
win下文件路径：C:\Users\你的用户名\pip\pip.ini  

清华源内容写： 
```
[global]  
index-url = https://pypi.tuna.tsinghua.edu.cn/simple  
[install]  
trusted-host=pypi.tuna.tsinghua.edu.cn   
```
### 推荐阿里源
阿里源内容写：   
```
[global]  
index-url = https://mirrors.aliyun.com/pypi/simple/   
[install]  
trusted-host=mirrors.aliyun.com
```

## liunx系统
linux下文件路径：
```
mkdir ~/.pip  
vim ~/.pip/pip.conf
```

清华源内容写：
```
[global]  
index-url = https://pypi.tuna.tsinghua.edu.cn/simple  
[install]  
trusted-host=pypi.tuna.tsinghua.edu.cn 
 ```
### 推荐阿里源
阿里源内容写：
```
[global]
index-url = https://mirrors.aliyun.com/pypi/simple/
[install]
trusted-host=mirrors.aliyun.com  
```
---
# conda  
conda  ----windows or ubuntu
命令行下两条命令即可  
```
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/ 
conda config --set show_channel_urls yes
```



windows下  

在清华源和中科大源之间自行选择  
1 添加清华源  

命令行中直接使用以下命令  
```
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge     

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/

# 设置搜索时显示通道地址
conda config --set show_channel_urls yes
```


2 添加中科大源
```
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/pkgs/main/  
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/pkgs/free/  
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge/  
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/msys2/  
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/bioconda/  
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/menpo/
conda config --set show_channel_urls yes
```

Linux下

将以上配置文件写在~/.condarc中
vim ~/.condarc
```
channels:
  - https://mirrors.ustc.edu.cn/anaconda/pkgs/main/
  - https://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge/
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
  - defaults
show_channel_urls: true
```



清华的anaconda镜像挂了，用中科大的镜像吧  
```
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/pkgs/free/  
conda config --set show_channel_urls yes 
```


参考：
* https://blog.csdn.net/qq_35608277/article/details/78714401
* https://blog.csdn.net/dream_allday/article/details/80344511
* https://blog.csdn.net/tangwenbo124/article/details/74784268

