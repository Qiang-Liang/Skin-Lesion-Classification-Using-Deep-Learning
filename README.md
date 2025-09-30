# 基于深度学习的皮肤病变分类项目

## 简介

本项目旨在使用深度学习技术对皮肤病变图像进行分类，以辅助皮肤癌的早期诊断。皮肤癌是常见的恶性肿瘤之一，早期诊断和治疗能极大提高患者的生存率。该项目通过构建和训练多种深度学习模型，实现了对不同类型皮肤病变图像的自动识别和分类，为医生提供可靠的诊断参考。

## 数据集

本项目使用的数据集是 ISIC-2018 challenge dataset
Dataset URL : https://challenge.isic-archive.com/data/#2018
数据集网址： https://challenge.isic-archive.com/data/#2018

该数据集包含了多种皮肤病变的图像，涵盖了 黑色素瘤 (MEL)、痣 (NV)、基底细胞癌 (BCC)、光化性角化病和上皮内癌 (AKIEC)、良性角化病样病变 (BKL)、皮肤纤维瘤 (DF)、血管病变 (VASC) 等多种类别。

数据预处理步骤包括：
- 图像尺寸调整
- 数据增强（如旋转、翻转、缩放）
- 数据集划分（训练集、验证集、测试集）

## 项目结构

```
.
├── Skin-Lesion-Classification-Using-Deep-Learning.ipynb   # 项目核心代码，包含数据处理、模型构建、训练和评估
└── README.md           # 项目说明文件
```

## 使用的模型

本项目实现了多种经典的卷积神经网络（CNN）模型进行对比实验。请在下方列表中勾选或添加您所使用的模型：

- [ ] VGG16 / VGG19
- [ ] ResNet (e.g., ResNet50)
- [ ] InceptionNet (e.g., InceptionV3)
- [ ] DenseNet
- [ ] MobileNet
- [ ] Xception
- [ ] 自定义CNN模型

## 环境要求

主要依赖库包括：
- Python (建议版本 3.7+)
- TensorFlow / Keras / PyTorch [请选择您使用的框架]
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- OpenCV

## 如何使用

1.  **克隆项目**
    ```bash
    git clone [您的项目git仓库地址]
    cd [您的项目目录]
    ```

2.  **安装依赖**
    ```bash
    pip install -r requirements.txt
    ```

3.  **准备数据集**
    请从 [数据集来源链接] 下载数据集，并将其放置在正确的目录下（如果代码中有指定）。

4.  **运行项目**
    使用 Jupyter Notebook 打开 `Skin-Lesion-Classification-Using-Deep-Learning.ipynb` 文件，并按顺序执行代码单元格。
    ```bash
    jupyter notebook Skin-Lesion-Classification-Using-Deep-Learning.ipynb
    ```

## 结果

请在此处展示您的模型在测试集上的表现。

- **准确率 (Accuracy)**: [填写您的最佳模型准确率]
- **混淆矩阵 (Confusion Matrix)**:
  （可以截图粘贴在此处）
- **其他指标**:
  - 精确率 (Precision)
  - 召回率 (Recall)
  - F1-Score

您也可以在此处添加一些模型性能的可视化图表，例如训练过程中的损失函数和准确率曲线。

## 贡献

欢迎对本项目提出改进意见！如果您有任何想法，请随时创建 Issue 或提交 Pull Request。

## 许可证

本项目采用 [MIT](https://opensource.org/licenses/MIT) 许可证。

