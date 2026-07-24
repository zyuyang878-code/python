# 💳 动态预算管理仪表盘 (Streamlit Budget Management App)

这是一个基于 **Python** 和 **Streamlit** 开发的交互式个人预算与消费管理 Web 应用。支持多账户分类管理、实时存取款与转账操作，并集成了 **Plotly** 动态图表展示。

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.25+-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## ✨ 核心功能亮点

* 📊 **动态数据看板**：实时计算总资产、总支出及分类数量，提供直观的 KPI 卡片展示。
* 📈 **可视化图表**：
* **消费占比饼图**：悬浮查看各分类支出明细与百分比。
* **账户余额柱状图**：动态对比各分类账户实时余额。
* 🛠️ **全套账目操作**：
* **自定义分类**：支持随时新增预算分类（如 Food, Entertainment, Health 等）。
* **存取款与转账**：提供直观的侧边栏交互窗口，支持分类间实时划转资金。
* 📜 **交易明细列表**：可按分类查看完整历史交易记录，自动标注收入与支出类型。
* ⚡ **响应式交互**：利用 `st.session_state` 实现免刷新数据持久交互。

---

## 🛠️ 技术栈

* **前端 GUI/UI**：[Streamlit](https://streamlit.io/)
* **图表绘制**：[Plotly Express](https://plotly.com/python/)
* **数据处理**：Pandas
* **开发语言**：Python 3

---

## 🚀 本地快速运行指南

### 1. 克隆/下载本项目
```bash
git clone [https://github.com/zyuyang878-code/python.git](https://github.com/zyuyang878-code/python.git)
cd python
