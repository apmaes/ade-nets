# ade-nets
专用于DAS地震记录检测的小型网络，模型文件为mini2.h5
```python
model = keras.models.load_model('mini2.h5')
model.summary()
```

检测前需要预处理，包括带通滤波和sta/lta变换。详见流程实例及https://ieeexplore.ieee.org/abstract/document/9681864/
