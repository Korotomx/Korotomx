<div align="center">

# Korotomx

**深度学习 · 计算机视觉 · GPU 部署 · 机器人**

从数学地基到模型在真实硬件上跑通。

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/) [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/) [![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-toolkit) [![TensorRT](https://img.shields.io/badge/TensorRT-000000?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/tensorrt) [![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)](https://docs.ros.org/) [![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)

</div>

---

| | | |
|:--:|:--:|:--:|
| [关于](#关于) | [方向](#方向) | [项目](#项目) |
| [技术栈](#技术栈) | [学习路径](#学习路径) | [笔记](#笔记) |

## 关于

我在搭一条完整、可复现的深度学习链路：模型背后的数学、训练代码，以及从 PyTorch 到 ONNX 再到 TensorRT 的部署路径。当前关注计算机视觉、高效推理和机器人感知。

学习过程记录在 [STD](https://github.com/Korotomx/STD)：一个把数学、AI 理论、CUDA/TensorRT、ROS 2 和技术写作连起来的知识库。

## 方向

| 方向 | 现在在做什么 |
|---|---|
| 数学地基 | 18.06 线性代数、6.041 概率、18.02 微积分，为 CS229 和模型推导打底 |
| AI 理论 | MIT 6.S191：CNN、RNN/Transformer、生成模型、强化学习、大规模训练 |
| GPU 部署 | CUDA 核函数、ONNX 导出、TensorRT engine、YOLO 的 GPU 预处理 |
| 机器人 | ROS 2 节点、话题/服务、感知到控制的完整链路 |
| 工程 | C++ / Python、CMake、Git、Linux / WSL2 |

## 项目

| 项目 | 内容 |
|---|---|
| [STD](https://github.com/Korotomx/STD) | 个人知识库：数学、AI、CUDA/TensorRT、ROS 2、英语与技术写作 |
| [DeepLearningRM](https://github.com/Korotomx/STD/tree/main/Artificial_Intelligence/DeepLearningRM) | RoboMaster 深度学习考核：ResNet-18 / MNIST；C++ ONNX + ROS 2 检测链路，mAP50 0.789，CPU 约 17 FPS |
| [TensorRT 部署](https://github.com/Korotomx/STD/tree/main/Artificial_Intelligence/CUDA) | YOLO 端到端部署：letterbox + 双线性缩放 + HWC→CHW 预处理写成 CUDA 核，直接喂给 engine |
| [ROS 2 课程项目](https://github.com/Korotomx/STD/tree/main/ROS2) | 乌龟追逐：节点、话题、服务、launch 文件与完整包结构 |

## 技术栈

| 层 | 工具 |
|---|---|
| 语言 | Python、C++ |
| 深度学习 | PyTorch、ONNX、TensorRT、Ultralytics YOLO |
| GPU | CUDA、cuDNN |
| 机器人 | ROS 2 |
| 环境 | Linux、WSL2、Git |

## 学习路径

```text
数学地基                 AI 理论                 GPU 部署                机器人
18.06 / 6.041 / 18.02  →  MIT 6.S191            →  CUDA / TensorRT      →  ROS 2
        │                       │                       │                      │
        └──────────────── 模型从推导到落地 ────────────────────────────────────┘
```

## 笔记

[STD](https://github.com/Korotomx/STD) 按科目组织：

- `Math/`：线性代数、概率、微积分
- `Artificial_Intelligence/`：6.S191、CUDA/TensorRT、RoboMaster 考核、Python
- `ROS2/`：通信、节点组织、课程项目
- `English/`、`Writing/`：技术英语与技术写作
- `Sight/`：长文与技术文章笔记

## 短版

- 学数学，读懂模型为什么成立
- 写 PyTorch，把模型训练出来
- 做 CUDA / TensorRT，把模型跑快
- 用 ROS 2，把模型接到机器人上

## 联系

- GitHub：[@Korotomx](https://github.com/Korotomx)
