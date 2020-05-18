# LSTM-Music🎵

该项目使您可以使用单个乐器的Midi音乐文件训练神经网络来生成🎹

<div align="center">

![](https://picreso.oss-cn-beijing.aliyuncs.com/v2-aefd22aa3df9c7ab0cff00c30d5d1849_720w.jpg)

## 需要的条件👀：

* Python 3.x
* 相关包：
	* Music21
	* Keras
	* Tensorflow
	* h5py

</div>

## 训练

只需要运行 `lstm-music.py`就行了

```
python lstm-music.py
```

网络将使用./midi_songs中的每个midi文件来训练网络。

 midi文件应仅包含钢琴乐

> 您可以在任何时间点停止该过程，会依据以训练内容生成对应模型

## 生成

训练之后就可以使用 predicter.py 生成音乐了

```
python predicter.py
```

您可以使用weights.hdf5文件立即运行预测文件

