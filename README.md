# 3D-
基于深度学习的3D室外场景自动生成算法，从点云数据中提取地形和地物信息，预测空间位置关系，恢复完整和细节丰富的3D室外场景。

数据准备
在此处下载对齐模型网并保存在 中。data/modelnet40_normal_resampled/

run
您可以使用以下代码运行不同的模式。

如果要对数据进行脱机处理，可以在第一次运行中使用。您可以在此处下载预处理的数据并将其保存在 中。--process_datadata/modelnet40_normal_resampled/
如果要在ModelNet10上进行训练，可以使用.--num_category 10
