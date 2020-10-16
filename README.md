# Jupyter-Lab主機: 
資工新建 JupyterLab 主機開放使用: jupyter.csie.nuu.edu.tw

# yolov3/Darknet 安裝
開啟 terminal
## 首先將darknet從github上clone下来
### $ git clone https://github.com/pjreddie/darknet.git
### $ cd darknet
### $ make

## 測試安裝是否正確
### $ ./darknet

## 下載官方訓練完畢的權重重(237MB),或者運行以下命令:
### $ wget https://pjreddie.com/media/files/yolov3.weights

## 下載完畢後,運行以下命令, 可以看到辨識結果
### $ ./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg


