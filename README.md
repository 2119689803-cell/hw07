# HW07 胸部X光肺炎二分类实战
## 目录结构
hw07/
├── train.ipynb        # 完整代码
├── report.md          # 实验报告
├── requirements.txt   # 依赖
├── pneumonia_model.h5 # 训练好的模型
├── figures/           # 图表
│   ├── train_curve.png
│   └── confusion_matrix.png
└── README.md

## 运行方式
1. Kaggle Notebook（推荐）
   - 直接挂载数据集：chest-xray-pneumonia
   - 运行 train.ipynb 全部单元格

2. 本地运行
   - 下载数据集并修改路径
   - 安装依赖：pip install -r requirements.txt

## 最终指标
测试集：
- 准确率：0.9263
- 精确率：0.9315
- 召回率：0.9564
- F1分数：0.9438
