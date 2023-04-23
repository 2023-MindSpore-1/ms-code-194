
# 背景描述
YOLOX是 YOLO(You Only Look Once) 系列的 anchor-free 版本，和经典的 YOLOv3~5 版本相比，它的网络设计更加的简单但是却拥有更加优秀的性能！YOLOX 致力于在学术研究和工业界之间架起一座桥梁。
# 需求描述
使用MindSpore复现论文YOLOX: Exceeding YOLO Series in 2021。
# 环境要求
软件平台：MindSpore
# 编程语言
模型开发及推理Demo：Python（MindSpore）
# 产出标准
1.使用MindSpore复现该论文，完成模型的训练、测试。
2.输出精度达标模型权重，并将其包装为推理Command-line Demo（Input: image or video, Output: result display or saving）。
3.分阶段输出数据处理，模型定义，训练过程三个关键代码的PyTorch和MindSpore的区别，并详细记录笔记。