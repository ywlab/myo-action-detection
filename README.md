# myo-action-detection
```bash
# 安装虚拟环境-python3
virtualenv venv
source venv/bin/activate

# 安装包
pip install -r requirements.txt

# 复制sdk文件夹到项目根目录

# make dir
mkdir models
mkdir output

# 复制模型到models文件夹

# 运行程序
python3 models.py load
```

## data collection

## data process

## train

## 手势

伸手指
单指：
大拇指：Thumbs_up
食指：
中指
无名指
小拇指

双指
大拇指+食指
大拇指+小指
食指+中指
食指+小指
无名指+小指

三指：
大拇指+食指+中指
大拇指+食指+小指
食指+中指+无名指
食指+无名指+小指
中指+无名指+小指

四指：
食指+中指+无名指+小指

五指伸开
食指按压桌面
中指按压桌面
五指呈现抓形状
握拳

## 离线收集数据
```bash
python3 collect_data_csv.py
```