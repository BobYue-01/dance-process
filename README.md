# 舞蹈处理

## 部署方式

### 新建虚拟环境

```bash
conda create -n pytorch-openpose python=3.7
conda activate pytorch-openpose
```

### clone 本项目

```bash
git clone https://github.com/BobYue-01/dance-process.git
cd ./dance-process
```

### 安装依赖

```bash
git clone https://github.com/BobYue-01/pytorch-openpose.git
cd ./pytorch-openpose
pip install -r requirements.txt
```

### 下载模型

* [dropbox](https://www.dropbox.com/sh/7xbup2qsn7vvjxo/AABWFksdlgOMXR_r5v3RwKRYa?dl=0)
* [baiduyun](https://pan.baidu.com/s/1IlkvuSi0ocNckwbnUe7j-g)
* [google drive](https://drive.google.com/drive/folders/1JsvI4M4ZTg98fmnCZLFM-3TeovnCRElG?usp=sharing)

`*.pth` files are pytorch model, you could also download caffemodel file if you want to use caffe as backend.

Download the pytorch models and put them in a directory named `model` in the project root directory
