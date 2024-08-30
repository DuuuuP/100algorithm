# 100 algorithm

## Documentation

   集成这100种生理信号预处理算法，这些算法提高数据预处理的效率，使得科研人员和临床医生能够更好地理解复杂的生理机制并提供更为精准的医疗服务。

## Features
  * method
    *  功能1：EEG，ECG，ECOG，EOG的预处理
    * 功能2：EEG，ECG，ECOG，EOG的特征提取
 * Supported Datasets
    * EEG
    * ECG
    * EOG
    * ECOG
## Dependencies
运行所需的最低依赖项：
* 环境
  - Python ≥ 3.10
*工具
  - NumPy ≥ 1.24
  - PyWavelets
  - Matplotlib
  - MNE ≥ 
  - SciPy ≥ 1.10
  - Matplotlib ≥ 3.6
  - Pytroch ≥
  - scikit-learn ≥
  - MetaBCI

## Installation

要使用这些库的指令：

```bash
pip install --upgrade pip
```

```bash
pip install numpy==1.21.0
```

## MetaBCI Installation

- 1.克隆存储库
```bash
（git clone https://github.com/TBC-TJU/MetaBCI.git）
```
- 2.更改项目目录
```bash
cd MetaBCI
```
- 3.安装所有要求
```bash
pip install -r requirements.txt 
```
- 4.以可编辑模式安装 brainda 包
```bash
pip install -e .
```
