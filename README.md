# 基于 GPR 的股票数据预测

随机过程课程项目（大作业），使用GPR分析股票数据。

## 数据

`./data/` 文件夹包含以下股票的 CSV 数据文件：
- MSFT.csv  (微软)
- NTDOF.csv (任天堂)
- NVDA.csv  (英伟达)
- SEGA.csv  (世嘉)
- SONY.csv  (索尼)
数据的时间跨度为2015-12-21至2025-12-19。

## 代码

`./code/main.ipynb` 是主要的Jupyter Notebook文件，包含数据处理、数据可视化和 GPR 模型。

## 结果

`./results/` 文件夹包含分析结果，包括：
- kernel.txt，内有针对各个股票训练得到的 GPR 核函数参数
- 各股票的子文件夹，每个文件夹保存该股票的原始数据折线图、标准化后的数据折线图、预测结果对比折线图

## 如何运行

1. 确保安装了Python和必要的库（如pandas, numpy, scikit-learn等）。
2. 打开 `code/main.ipynb` 并运行所有单元格。

## 参考文献
[1]	M.Ebden, " Gaussian Processes for Regression An Quick Introduction".
[2]	H.M.Wallace, “Introduction to Gaussian Process Regression”
[3]	M.T. Farrell, et al, “Gaussian Process Regression Models for Predicting Stock Trends”.
[4]	Long-term Stock Market Forecasting using Gaussian Processes
[5]	https://scikit-learn.org/stable/modules/generated/sklearn.gaussian_process.GaussianProcessRegressor.html
[6]	https://github.com/gdroguski/GaussianProcesses/
