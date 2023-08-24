论文名称： Continuous Convolutional Neural Network with 3D Input for EEG-Based Emotion Recognition
1. 运行get_1D_data.py计算每个原始 mat 文件的微分熵。每个.mat 文件档的 DE 特征将存储在1D_dataset文件夹中。
2.1D_to_3D.py用于将 1维数据转换为 3 维格式，用于训练模型。
3.使用 cnn.py 来训练和测试模型（10 倍交叉验证），每个折叠的结果将保存在一个.xls文件文件（您可以在result文件夹中找到这些.xls文件）。
4.count_accuracy.py用于总结模型的最终准确性。生成的.xls文件可以在 。/result/summary文件夹中找到。