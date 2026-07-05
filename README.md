# 📊 Data Analysis 数据分析案例集

> Python 数据分析自学笔记与实践案例，涵盖 Pandas、Matplotlib、数据清洗、可视化与简单建模。  
> **德邦经营方向 · 海豚生** 7 天实战练习已整合进本仓库。

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-数据分析-green.svg)](https://pandas.pydata.org/)

---

## 📖 项目简介

本仓库包含两部分内容：

1. **16 个经典数据分析 Notebook** — Pandas / Matplotlib 入门案例
2. **德邦经营方向 7 天实战练习** — 基于零担物流运单数据的完整经营分析（★ 推荐）

每个 Notebook 都遵循：**数据读取 → 清洗 → 分析 → 可视化 → 经营结论**。

---

## 🐬 德邦经营方向 · 7 天实战（海豚生）

> 详细复盘总结见：[docs/7天练习复盘总结_海豚生.md](./docs/7天练习复盘总结_海豚生.md)

| Day | 主题 | 文件 | 经营问题 |
|-----|------|------|---------|
| 1 | KPI 总览 | [练习01_Day1_KPI入门_海豚生.ipynb](./练习01_Day1_KPI入门_海豚生.ipynb) | 整体赚多少钱？ |
| 2 | 区域诊断 | [Day2_Region_Analysis.ipynb](./Day2_Region_Analysis.ipynb) | 哪个区拖后腿？ |
| 3 | 客户 ABC | [Day3_Customer_ABC.ipynb](./Day3_Customer_ABC.ipynb) | 谁是大客户？ |
| 4 | 可视化汇报 | [Day4_Visualization.ipynb](./Day4_Visualization.ipynb) | 怎么做周会 PPT？ |
| 5 | 服务质量 | [Day5_Service_Quality.ipynb](./Day5_Service_Quality.ipynb) | 准时吗？满意吗？ |
| 6 | 趋势预警 | [Day6_Trend_Alert.ipynb](./Day6_Trend_Alert.ipynb) | 营收涨还是跌？ |
| 7 | 综合报告 | [Day7_Final_Report.ipynb](./Day7_Final_Report.ipynb) | 完整经营诊断 ★ |

**练习数据：** [data/orders.csv](./data/orders.csv)（150 条德邦向示例运单）

### 快速开始（7 天练习）

```bash
git clone https://github.com/njq0204/data-analysis.git
cd data-analysis
pip install pandas matplotlib jupyter
jupyter notebook Day7_Final_Report.ipynb   # 直接看综合报告
# 或从 Day1 按顺序练习
```

### 7 天练习核心结论（示例数据）

| 维度 | 关键发现 |
|------|---------|
| 整体 KPI | 营收 32.8 万，毛利率 27.28%（高于 25% 基准） |
| 区域 | 华东营收最高；华北毛利率相对最低 |
| 客户 | A 类 8 个客户占 75.5% 营收，集中度较高 |
| 产品 | 大件快递毛利率最高（~29.5%） |
| 服务质量 | 准时率 74%、客诉率 14%，均未达标 |
| 趋势 | 2025-05 营收环比 -12.88%，触发紧急预警 |

---

## 📁 经典案例目录

### 🎨 数据可视化

| Notebook | 内容 |
|----------|------|
| [matplotlib.ipynb](./matplotlib.ipynb) | Matplotlib 基础绘图 |
| [散点图.ipynb](./散点图.ipynb) | 散点图绘制与分析 |
| [绘制条形图.ipynb](./绘制条形图.ipynb) | 条形图实战 |
| [绘制直方图.ipynb](./绘制直方图.ipynb) | 直方图与分布分析 |

### 🐼 Pandas 数据处理

| Notebook | 内容 |
|----------|------|
| [pandas实践--2012美国总统竞选赞助数据分析.ipynb](./pandas实践--2012美国总统竞选赞助数据分析.ipynb) | 竞选赞助数据分析 |
| [对比Excel.ipynb](./对比Excel.ipynb) | Pandas vs Excel 操作对比 |
| [对比Excel2.ipynb](./对比Excel2.ipynb) | Pandas vs Excel 进阶对比 |

### 🔍 经典数据集分析

| Notebook | 内容 |
|----------|------|
| [泰坦尼克号.ipynb](./泰坦尼克号.ipynb) | 泰坦尼克号生存率分析 |
| [红酒数据集分析.ipynb](./红酒数据集分析.ipynb) | 红酒品质数据分析 |
| [个人收入水平分析.ipynb](./个人收入水平分析.ipynb) | 收入分布与影响因素 |
| [短租数据分析.ipynb](./短租数据分析.ipynb) | 短租平台数据探索 |
| [朝阳医院.ipynb](./朝阳医院.ipynb) | 医院数据案例分析 |
| [python案例分析--淘宝.ipynb](./python案例分析--淘宝.ipynb) | 淘宝数据爬取与分析 |

### 📈 机器学习入门

| Notebook | 内容 |
|----------|------|
| [线性回归.ipynb](./线性回归.ipynb) | 线性回归模型实战 |

### 💼 业务场景模拟

| Notebook | 内容 |
|----------|------|
| [假如你是某连锁超市的数据分析师.ipynb](./假如你是某连锁超市的数据分析师.ipynb) | 超市销售数据分析 |
| [假如你是某银行的数据分析师.ipynb](./假如你是某银行的数据分析师.ipynb) | 银行业务数据分析 |

---

## 🛠️ 环境要求

```bash
Python >= 3.8
pip install pandas matplotlib numpy jupyter seaborn scikit-learn
```

> 若遇 `numpy 2.x` 兼容问题：`pip install "numpy<2"`

---

## 📚 推荐学习路线

### 路线 A：德邦经营实战（有业务场景）

```
Day1 KPI → Day2 区域 → Day3 客户 → Day4 可视化 → Day5 服务质量 → Day6 趋势 → Day7 综合报告
```

### 路线 B：经典入门（纯技能）

```
对比Excel.ipynb → 泰坦尼克号.ipynb → 散点图.ipynb → 线性回归.ipynb
```

---

## 📂 项目结构

```
data-analysis/
├── data/
│   └── orders.csv                         # 德邦向练习数据
├── docs/
│   └── 7天练习复盘总结_海豚生.md           # 每日练习+进阶题+复盘
├── 练习01_Day1_KPI入门_海豚生.ipynb        # Day 1
├── Day2_Region_Analysis.ipynb             # Day 2
├── Day3_Customer_ABC.ipynb                # Day 3
├── Day4_Visualization.ipynb               # Day 4
├── Day5_Service_Quality.ipynb             # Day 5
├── Day6_Trend_Alert.ipynb                 # Day 6
├── Day7_Final_Report.ipynb                # Day 7 收官
├── output/                                # 练习输出图表
└── （16 个经典案例 Notebook）
```

---

## 🙏 致谢

- 经典案例 Fork 自 [michael-wy/data-analysis](https://github.com/michael-wy/data-analysis)
- 7 天德邦经营练习 · 海豚生 · 2026

---

## 📬 联系方式

- GitHub：[@njq0204](https://github.com/njq0204)
- 关联项目：[logistics-ops-toolkit](https://github.com/njq0204/logistics-ops-toolkit)（物流经营数据分析平台）

---

⭐ 如果这个仓库对你有帮助，欢迎 Star 支持一下！
