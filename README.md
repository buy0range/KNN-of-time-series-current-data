# KNN-of-time-series-current-data
## Introduction / 简介
The notebook performs a detailed analysis using the K-Nearest Neighbors (KNN) algorithm. It includes data preparation, preprocessing, and visualization steps. The dataset used in this analysis contains current measurements under healthy and unhealthy conditions.

该笔记本使用 K-近邻算法 (KNN) 进行详细分析，包括数据准备、预处理和可视化步骤。分析中使用的数据集包含健康和异常条件下的电流测量数据。

## Dataset / 数据集
The dataset consists of three CSV files:

healthy.csv: Contains current measurements under healthy conditions.

0.7inner-100watt.csv: Contains current measurements under unhealthy conditions with 100 watts.

0.7inner-200watt.csv: Contains current measurements under unhealthy conditions with 200 watts.

数据集包含三个 CSV 文件：

healthy.csv：健康条件下的电流测量数据。

0.7inner-100watt.csv：100 瓦异常条件下的电流测量数据。

0.7inner-200watt.csv：200 瓦异常条件下的电流测量数据。

## Dependencies / 依赖项
To run this notebook, you need the following Python libraries:

运行此笔记本需要以下 Python 库：

pandas

numpy

matplotlib

seaborn

scipy

scikit-learn

## Notebook Structure / 笔记本结构
The notebook is structured as follows:

笔记本的结构如下：

Import Libraries: Import necessary Python libraries.
导入库：导入必要的 Python 库。

Read Dataset: Load the dataset from CSV files.
读取数据集：从 CSV 文件加载数据集。

Preprocess Data: Clean and preprocess the data, including deduplication and timestamp processing.
数据预处理：清理和预处理数据，包括去重和时间戳处理。

Process Data: Further processing, including adding extra rows to maintain consistent lengths.
数据处理：进一步处理数据，包括添加额外行以保持长度一致。

Plot Figures: Visualize the data using plots.
绘制图表：使用图表可视化数据。

KNN Analysis: Perform KNN classification and evaluate the model.
KNN 分析：执行 KNN 分类并评估模型。

## Results / 结果
The notebook includes visualizations and classification results using the KNN algorithm. The accuracy and classification report are provided to evaluate the model's performance.

笔记本包括使用 KNN 算法的可视化和分类结果。提供了准确性和分类报告以评估模型的性能。

## Contributing / 贡献
Contributions are welcome! Please fork the repository and create a pull request with your changes.

欢迎贡献！请 fork 本仓库并提交 pull request。

## License / 许可证
This project is licensed under the MIT License. See the LICENSE file for details.

本项目采用 MIT 许可证。详情请参阅 LICENSE 文件。





















