# ProjectTemplate
A reusable template for research projects, providing a structured layout for data, notebooks, models, and scripts. Clone to quickly start new research with a consistent setup.


my_project/
│
├── data/
│   ├── raw/                # 原始数据
│   ├── processed/          # 处理后的数据
│   └── external/           # 外部数据
│
├── notebooks/              # Jupyter 笔记本
│   └── ...
│
├── src/
│   ├── __init__.py
│   ├── data/               # 数据处理脚本
│   ├── features/           # 特征工程脚本
│   ├── models/             # 模型定义与训练脚本
│   └── visualization/      # 可视化脚本
│
├── models/                 # 训练好的模型
│   └── ...
│
├── reports/                # 报告与结果
│   └── figures/            # 可视化图表
│
├── .gitignore
├── README.md
├── requirements.txt
├── environment.yml         # 环境配置
└── LICENSE
