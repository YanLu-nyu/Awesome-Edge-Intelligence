# Edge Intelligence
A curated list of research in edge intelligent systems. I also summarize some papers if I think they are really interesting. Insipred by [survey](https://arxiv.org/abs/1905.10083), I split papers into **4** research topics: 1) model compression and optimization for specific hardware; 2) optimization on heterogeneous resources; 3) privacy and security; 4) continual and collaborative learning. Among them, I'm very interested in the second and fourth one. To guide other researchers and developers to read it efficiently, I also provide a curated list of self-learning resources on heteogeneous computing. 
## Definitions
### Edge compution
Edge computing refers to the enabling techniques allowing computation to be performed at the edge of the network on downstream data on behalf of cloud services and upstream data on behalf of IoT services. Here we define “edge” as any computing and network resources along the path between data sources and cloud data centers. <br>
[1] [Shi et al. Edge Computing: Vision and Challenges. IEEE Internet of Things Journal 2016.](https://www.researchgate.net/publication/303890546_Edge_Computing_Vision_and_Challenges) 
### Edge intelligence
Edge intelligence describes a process where data is analyzed and aggregated in a spot close to where it is captured in a network. The intelligent edge, also described as “intelligence at the edge,” has important ramifications for distributed networks including the internet of things (IoT).<br>
From [techopedia website](https://www.techopedia.com/definition/32559/intelligent-edge)
## Video
1. [Intelligent Edge Session (Microsoft Faculty Summit, 2018).](https://youtu.be/EbRQMncZ5XY)
## Survey
[1] [Satyanaryanan et al. The Case for VM-Based Cloudlets in Mobile Computing. IEEE Pervasive Computing 2009.](https://www.cs.cmu.edu/~satya/docdir/satya-ieeepvc-cloudlets-2009.pdf)<br>
[2] [Zhi et al. Edge Intelligence: Paving the Last Mile of Artificial Intelligence with Edge Computing. Proceedings of the IEEE (2019).](https://arxiv.org/abs/1905.10083) <br>
[3] [Edge Intelligence for industry. White Paper of IEC (2019).](https://www.iec.ch/whitepaper/edgeintelligence/)
## Researchers and labs
### Researchers
1. [Victor Bahl (MSR)](https://www.microsoft.com/en-us/research/people/bahl/)
2. [Mahadev Satyanarayanan (CMU)](http://www.cs.cmu.edu/~satya/)
3. [Ramon Caceres (Google)](http://www.kiskeya.net/ramon/#pubs)
4. [Nigel Davies (Lancaster University, U.K.)](https://www.lancaster.ac.uk/people-profiles/nigel-davies)
5. [Roy Want (Google)](http://www.roywant.com/cv/vita.htm)
6. [Yunxin Liu (MSRA)](https://www.microsoft.com/en-us/research/people/yunliu/)
7. [Umakishore Ramachandran (Gatech)](https://www.cc.gatech.edu/~rama/)
### Labs
1. [Elijah and Gabriel (CMU)](http://elijah.cs.cmu.edu/)
2. [Machine Learning on the Edge (MSR)](https://www.microsoft.com/en-us/research/project/machine-learning-edge/)
## Research opportunities
### Model compression and optimization for specific hardware
#### General approaches for compression and optimization
1. Reduce the complexity of inputs.
2. Pre-computations on independent workload.
3. Share architectures with many CV tasks.
4. Cache in video processing.
#### Paper
[1] [Han et al. MCDNN: An approximation-based execution framework for deep stream processing under resource constraints. In MobiSys'16.](https://homes.cs.washington.edu/~arvind/papers/mcdnn.pdf)<br>
[2] [Huynh et al. DeepMon: Mobile GPU-based Deep Learning Framework for Continuous Vision Applications. In MobiSys'17.](https://nsr.cse.buffalo.edu/mobisys_2017/papers/pdfs/mobisys17-paper07.pdf)<br>
[3] [Xu et al. DeepCache: Principled Cache for Mobile Deep Vision. In MobiCom'18.](https://arxiv.org/pdf/1712.01670.pdf)
### Optimization on heterogeneous resources
#### [awesome heterogeneous computing](https://github.com/YanLu-nyu/Awesome-Edge-Intelligence/blob/master/awesome-heterogeneous-computing.md)
In this note, I collect some useful resources (book, blog, paper and github) for heterogeneous computing. From my perspective, learning heterogeneous computing will help us understand the limitation of current optimization on heterogeneous resources deeply.
#### Paper
[1] [Liu et al. On-Demand Deep Model Compression for Mobile Devices: A Usage-Driven Model Selection Framework. In MobiSys'18.](https://tik-old.ee.ethz.ch/file//79a7dd6f6370f809e6180c0746232283/mobisys18-liu.pdf)<br>
[2] [Fany et al. NestDNN: Resource-Aware Multi-Tenant On-Device Deep Learning for Continuous Mobile Vision. In MobiCom'18.](https://arxiv.org/abs/1810.10090)<br>
[3] [Cao et al. Efficient and Effective Sparse LSTM on FPGA with Bank-Balanced Sparsity. In FPGA'19.](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/FPGA2019_final.pdf)<br>
[4] [Cao et al. SeerNet: Predicting Convolutional Neural Network Feature-Map Sparsity through Low-Bit Quantization. In CVPR'19.](http://openaccess.thecvf.com/content_CVPR_2019/papers/Cao_SeerNet_Predicting_Convolutional_Neural_Network_Feature-Map_Sparsity_Through_Low-Bit_Quantization_CVPR_2019_paper.pdf)<br>
[5] [Lee et al. MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors. In MobiCom'19.](https://arxiv.org/pdf/1908.07985.pdf)<br>
[6] [Zhang et al. MobiPose: Real-Time Multi-PersonPose Estimation on Mobile Devices. In SenSys'20.](https://dl.acm.org/doi/10.1145/3384419.3430726#pill-authors__contentcon)<br>
[7] [Jiang et al. Profiling and Optimizing Deep Learning Inference on Mobile GPUs. In APSys'20.](https://dl.acm.org/doi/10.1145/3409963.3410493)<br>
[8] [Wu et al. EMO: Real-Time Emotion Recognition from Single-Eye Images for Resource-Constrained Eyewear Devices. In MobiSys'20.](https://dl.acm.org/doi/abs/10.1145/3386901.3388917)<br>
### Privacy and security (models and data)
[1] [Lee et al. Occlumency: Privacy-preserving Remote Deep-learning Inference Using SGX. In MobiCom'19.](http://soar.group/pubs/Occlumency.MobiCom19.pdf)
### Continual and collaborative learning
[1] [Lu et al. Collaborative Learning between Cloud and End Devices: An Empirical Study on Location Prediction. In SEC'19.](https://www.microsoft.com/en-us/research/publication/collaborative-learning-between-cloud-and-end-devices-an-empirical-study-on-location-prediction/)<br>
[2] [Yang et al. Characterizing Impacts of Heterogeneity in Federated Learning upon Large-Scale Smartphone Data. In WWW'21.]
## Applications
[1] [Zeng et al. MobileDeepPill: A Small-Footprint Mobile Deep Learning System for Recognizing Unconstrained Pill Images. In MobiSys'17.](https://www.egr.msu.edu/~mizhang/papers/2017_MobiSys_MobileDeepPill.pdf)<br>
[2] [Cao et al. DeQA: On-Device Question Answering. In MobiSys'19.](https://awk.ai/assets/deqa.pdf)<br>

