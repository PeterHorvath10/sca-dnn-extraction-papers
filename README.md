# Physical Side Channel Attacks on Neural Networks
Collection of papers on Deep Neural Network model extraction through Physical Side Channels. 

This collection is *regularly updated*, starting with the initial version featured in our paper: [SoK: Neural Network Extraction Through Physical Side Channels](https://www.usenix.org/conference/usenixsecurity24/presentation/horvath). Péter Horváth, Dirk Lauret, Zhuoran Liu, and Lejla Batina. 

Listed papers are divided into three categories based on their goals: Architecture extraction, Parameter extraction, and Input recovery.

# Architecture extraction
- [USENIX'19] [Reverse engineering of neural network architectures through electromagnetic side channel.](https://www.usenix.org/conference/usenixsecurity19/presentation/batina)
- [ICCAD'20] [Machine Learning and Hardware security: Challenges and Opportunities](https://ieeexplore.ieee.org/document/9256522)
- [ASPLOS'20] [DeepSniffer: A DNN Model Extraction Framework Based on Learning Architectural Hints.](https://dl.acm.org/doi/10.1145/3373376.3378460) 
- [ACNS'20] [Simple Electromagnetic Analysis Against Activation Functions of Deep Neural Networks](https://link.springer.com/chapter/10.1007/978-3-030-61638-0_11)
- [TCAS-I'20] [Open DNN Box by Power Side-Channel Attack](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9000972)
- [HOST'20] [DeepEM: Deep Neural Networks Model Recovery through EM Side-Channel Information Leakage](https://ieeexplore.ieee.org/document/9300274)
- [AIHWS'21] [On reverse engineering neural network implementation on GPU.](https://eprint.iacr.org/2021/720)
- [ISCAS'21] [Extraction of Binarized Neural Network Architecture and Secret Parameters Using Side-Channel Information](https://ieeexplore.ieee.org/document/9401626)
- [ISVLSI'21] [Stealing Machine Learning Parameters via Side Channel Power Attacks](https://ieeexplore.ieee.org/document/9516772)
- [USENIX'22] [Can one hear the shape of a neural network?: Snooping the GPU via magnetic side channel.](https://www.usenix.org/conference/usenixsecurity22/presentation/maia)
- [SPW'22] [Clairvoyance: Exploiting Far-field EM Emanations of GPU to "See" Your DNN Models through Obstacles at a Distance](https://ieeexplore.ieee.org/document/9833894)
- [CARDIS'23] [Like an Open Book? Read Neural Network Architecture with Simple Power Analysis on 32-Bit Microcontrollers](https://link.springer.com/chapter/10.1007/978-3-031-54409-5_13)
- [SENSORS'23] [SNATCH: Stealing neural network architecture from ML accelerator in intelligent sensors](https://ieeexplore.ieee.org/document/10324872)
- [AIHWS'24] [CNN Architecture Extraction on Edge GPU](https://link.springer.com/chapter/10.1007/978-3-031-61486-6_10)
- [SP'24] [Side-Channel-Assisted Reverse-Engineering of Encrypted DNN Hardware Accelerator IP and Attack Surface Exploration](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a001/1RjE9FWOWsw)
- [CHES'24] [TPUXtract: An Exhaustive HyperparameterExtraction Framework](https://tches.iacr.org/index.php/TCHES/article/view/11923/11782)
# Parameter extraction
- [USENIX'19] [Reverse engineering of neural network architectures through electromagnetic side channel.](https://www.usenix.org/conference/usenixsecurity19/presentation/batina)
- [ICCAD'20] [Machine Learning and Hardware security: Challenges and Opportunities](https://ieeexplore.ieee.org/document/9256522)
- [HOST'20] [MaskedNet: The First Hardware Inference Engine Aiming Power Side-Channel Protection](https://www.computer.org/csdl/proceedings-article/host/2020/09300276/1pQJ1p6cl0c)
- [ISCAS'20] [Model reverse-engineering attack using correlation power analysis against systolic array based neural network accelerator.](https://ieeexplore.ieee.org/document/9180580)
- [TRANS-A'21] [Model Reverse-Engineering Attack against Systolic-Array-Based DNN Accelerator Using Correlation Power Analysis](https://www.jstage.jst.go.jp/article/transfun/E104.A/1/E104.A_2020CIP0024/_article/-char/ja/)
- [ISCAS'21] [Extraction of Binarized Neural Network Architecture and Secret Parameters Using Side-Channel Information](https://ieeexplore.ieee.org/document/9401626)
- [IoT-J'21] [Leaky Nets: Recovering Embedded Neural Network Models and Inputs Through Simple Power and Timing Side-Channels—Attacks and Defenses](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9360858)
- [JETC'22] [Power-based attacks on spatial DNN accelerators.](https://dl.acm.org/doi/10.1145/3491219)
- [CARDIS'22] [A Practical Introduction to Side-Channel Extraction of Deep Neural Network Parameters](https://link.springer.com/chapter/10.1007/978-3-031-25319-5_3)
- [SP'24] [Side-Channel-Assisted Reverse-Engineering of Encrypted DNN Hardware Accelerator IP and Attack Surface Exploration](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a001/1RjE9FWOWsw)
- [USENIX'25] [BarraCUDA: Edge GPUs do Leak DNN Weights](https://arxiv.org/abs/2312.07783)

# Input recovery
- [ACSAC'18] [I Know What You See: Power Side-Channel Attack on Convolutional Neural Network Accelerators](https://dl.acm.org/doi/10.1145/3274694.3274696)
- [SIGSAC'19] [Poster: Recovering the input of neural networks via single shot side-channel attacks.](https://dl.acm.org/doi/10.1145/3319535.3363280)
- [SmartIoT'19] [Floating-Point Multiplication Timing Attack on Deep Neural Network](https://ieeexplore.ieee.org/document/8896403)
- [IoT-J'21] [Leaky Nets: Recovering Embedded Neural Network Models and Inputs Through Simple Power and Timing Side-Channels—Attacks and Defenses](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9360858)
- [ARES'23] [You Only Get One-Shot: Eavesdropping Input Images to Neural Network by Spying SoC-FPGA Internal Bus](https://dl.acm.org/doi/abs/10.1145/3600160.3600189)


```
@inproceedings{horvath2024sok,
  title={SoK: Neural Network Extraction Through Physical Side Channels},
  author={Horv{\'a}th, P{\'e}ter and Lauret, Dirk and Liu, Zhuoran and Batina, Lejla},
  year={2024},
  booktitle={USENIX Security}
}
```

