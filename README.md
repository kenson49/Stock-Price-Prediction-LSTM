# Stock-Price-Prediction-LSTM
A LSTM model for stock price prediction.
# 📈 LSTM 股票价格预测模型

这是一个基于深度学习的股票价格预测项目。它使用 **长短期记忆网络 (LSTM)** 来分析历史股价数据，并尝试预测未来的股价走势。本项目以 **特斯拉 (TSLA)** 为例进行了演示。

> ⚠️ **免责声明：** 股票市场具有高度不确定性，本模型仅供学习和研究使用，**不构成任何投资建议**。预测结果仅供参考，请勿盲目跟从。

---

### 🛠️ 技术栈

- **Python 3.8+**
- **深度学习框架:** Keras (TensorFlow 后端)
- **数据获取:** yfinance
- **数据分析:** NumPy, Pandas
- **可视化:** Matplotlib
- **算法:** LSTM (Long Short-Term Memory)

### 📊 核心功能

- 📥 **数据获取：** 使用 `yfinance` 自动下载指定股票的历史数据。
- 🧹 **数据预处理：** 使用 MinMaxScaler 对数据进行归一化处理。
- 🧠 **模型构建：** 构建包含 Dropout 层的三层 LSTM 神经网络，防止过拟合。
- 📈 **可视化：** 绘制训练损失曲线、实际价格与预测价格对比图。
- 🔮 **未来预测：** 支持预测未来 N 天的股价走势。

### 🚀 快速开始

#### 1. 克隆仓库
```bash
git clone https://github.com/你的用户名/Stock-Price-Prediction-LSTM.git
cd Stock-Price-Prediction-LSTM
