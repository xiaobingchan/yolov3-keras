**如果帮到您请给个 star ✨✨✨，您的 star 是我最大的鼓励！**

# Yolov3 keras 漂浮物检测 万能运行 数据集制作
---

# 1.环境准备
首先确保自己的环境：

```text
pip install -i https://pypi.douban.com/simple/ --trusted-host=pypi.douban.com/simple -r requirements.txt
```

### 2.文件放置规范
1,图片放在：VOCdevkit\VOC2007\JPEGImages
2,xml标签放在：VOCdevkit\VOC2007\Annotations

3，训练集信息放train.txt，例如:  文件路径 物体1的x1,y1,x2,y2,物体1类别  物体2的x1,y1,x2,y2,物体2类别，如：

```shell
E:\keras-yolo3\VOCdevkit\VOC2007\JPEGImages\000000.jpg 60,66,910,1108,0
```

4,权重yolo_weights.h5放在model_data文件夹下面，下载地址：链接：https://pan.baidu.com/s/1GQfN4y1v0kTkq3nGf8oaGQ  ， 提取码：z7uv 

5,修改model_data/voc_classes.txt，里面放你的识别类名称，如

```shell
hat
person
```

### 3.开始训练
```shell script
python train.py
```

# 识别
运行命令：
```shell script
python yolo_video.py
```

**如果帮到您请给个 star ✨✨✨，您的 star 是我最大的鼓励！**

**如果能帮到您的项目快速落地，可以 buy me a coffee ☕**
![](./doc/BuyMeACoffee.jpg)


也可以加我的 WeChat 和我一起探讨更多的可能！
![](./doc/WeChat.jpg)
