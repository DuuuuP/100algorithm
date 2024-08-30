# 算法说明

## 简介

   集成这100多种生理信号预处理算法，这些算法提高数据预处理的效率，使得科研人员和临床医生能够更好地理解复杂的生理机制并提供更为精准的医疗服务。

## 功能示例
  * scipy示例 
    * High-pass filtering（高通滤波）
    * Low-pass filtering（低通滤波）
    * Band-pass filtering（带通滤波）
    * Band-stop filtering（带阻滤波）
    * Adaptive filtering（自适应滤波）
  * numpy示例
    * FFT（快速傅立叶变换）
    * FFT（快速傅立叶变换）
    * STFT（短时傅里叶变换）
  * mne示例
    * ICA（独立成分分析）
    * 伪迹去除
    * Mean Amplitude Difference（平均幅度差）
    * 脑电图（EEG）拓扑图
    * Mean Amplitude Difference（平均幅度差）
  * MetaBCI示例
    * Decomposition Methods
    * Manifold Learning
    * Deep Learning
    * Transfer Learning
  * scikit-learn示例
    * PCA（主成分分析）
    * PLS（偏最小二乘回归）
    * 线性判别分析（LDA、SWLDA、SKLDA、BLDA、STDA）
    * DSP（判别空间模式）
  * troch示例
    * LSTM（长短期记忆网络 ）
    * RNN（递归神经网络）
    * CNN（卷积神经网络）
  * 支持的数据集
    * EEG
      *  P300
      *  ssvep
      *  MI
      *  情绪识别
    * ECG
    * EOG
    * ECOG

全部算法请查看算法平台，详细支撑算法相关工具和版本请参考下面依赖！！！

## 依赖
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

## 安装

要使用这些库的指令：
pip install package_name == version

### 示例

```bash
pip install --upgrade pip
```

```bash
pip install numpy==1.21.0
```
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
```

## MetaBCI 安装方法

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
