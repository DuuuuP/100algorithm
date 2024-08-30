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
  - Python ≥ 3.9.9
* 工具
   - cecbutils ≥ 0.0.5
   - certifi ≥ 2024.7.4
   - charset-normalizer ≥ 3.3.2
   - contourpy ≥ 1.2.1
   - cycler  ≥ 0.12.1
   - decorator ≥ 5.1.1
   - fonttools ≥ 4.53.1
   - future ≥ 1.0.0
   - idna ≥ 3.7
   - importlib_resources ≥ 6.4.0
   - Jinja2 ≥ 3.1.4
   - joblib ≥ 1.4.2
   - kiwisolver ≥ 1.4.5
   - lazy_loader ≥ 0.4
   - MarkupSafe ≥ 2.1.5
   - matplotlib ≥ 3.9.1
   - mne ≥ 1.7.1
   - metabci
   - nolds ≥ 0.5.2
   - numpy ≥ 1.26.4
   - packaging ≥ 24.1
   - pandas ≥ 2.2.2
   - pillow  ≥ 10.4.0
   - pip  ≥ 24.1.2
   - platformdirs ≥ 4.2.2
   - pooch ≥ 1.8.2
   - pyparsing ≥ 3.1.2
   - python-dateutil ≥ 2.9.0.post0
   - pytz ≥ 2024.1
   - PyWavelets ≥ 1.5.0
   - requests ≥ 2.31.0
   - scikit-learn ≥ 1.5.1
   - scipy ≥ 1.13.1
   - setuptools ≥ 57.5.0
   - six ≥ 1.16.0
   - threadpoolctl ≥ 3.5.0
   - torch ≥ 2.2.0
   - tqdm ≥ 4.66.4
   - typing ≥ 3.7.4.3
   - tzdata ≥ 2024.1
   - urllib3 ≥ 2.2.2
   - wheel ≥ 0.37.0
   - zipp ≥ 3.19.2

## Installation

要使用这些库的指令：
pip install package_name == version

###　Example

```bash
pip install --upgrade pip
```

```bash
pip install numpy==1.21.0
```
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
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
