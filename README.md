# Jupyter-Lab
資工新建 JupyterLab 主機開放使用: jupyter.csie.nuu.edu.tw

# yolov3/Darknet 安裝
開啟 terminal
## 首先将darknet从github上clone下来
### $ git clone https://github.com/pjreddie/darknet.git
### $ cd darknet
### $ make

## 測試安裝是否正確
### $ ./darknet

## 下载官方训练完毕的权重(237MB),或者运行以下命令:
### $ wget https://pjreddie.com/media/files/yolov3.weights

## 下载完毕后,运行以下命令, 可以看到辨識結果
### $ ./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg


