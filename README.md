# Edge Intelligence
Intelligent Edge computing research notes
## Definitions
### Edge compution
Edge computing refers to the enabling techniques allowing computation to be performed at the edge of the network on downstream data on behalf of cloud services and upstream data on behalf of IoT services. Here we define “edge” as any computing and network resources along the path between data sources and cloud data centers. <br>
[1] [Shi et al. Edge Computing: Vision and Challenges. IEEE Internet of Things Journal 2016.](https://www.researchgate.net/publication/303890546_Edge_Computing_Vision_and_Challenges) 
### Edge intelligence (todo)
## Survey
[1] [Satyanaryanan et al. The Case for VM-Based Cloudlets in Mobile Computing. IEEE Pervasive Computing 2009.](https://www.cs.cmu.edu/~satya/docdir/satya-ieeepvc-cloudlets-2009.pdf)<br>
[2] [Zhi et al. Edge Intelligence: Paving the Last Mile of Artificial Intelligence with Edge Computing. Proceedings of the IEEE (2019).](https://arxiv.org/abs/1905.10083) <br>
## Researchers and labs
### Researchers
1. [Victor Bahl (MSR)](https://www.microsoft.com/en-us/research/people/bahl/)
2. [Mahadev Satyanarayanan (CMU)](http://www.cs.cmu.edu/~satya/)
3. [Ramon Caceres (Google)](http://www.kiskeya.net/ramon/#pubs)
4. [Nigel Davies (Lancaster University, U.K.)](https://www.lancaster.ac.uk/people-profiles/nigel-davies)
5. [Roy Want (Google)](http://www.roywant.com/cv/vita.htm)
6. [Yunxin Liu (MSRA)](https://www.microsoft.com/en-us/research/people/yunliu/)
### Labs
1. [Elijah and Gabriel (CMU)](http://elijah.cs.cmu.edu/)
2. [Machine Learning on the Edge (MSR)](https://www.microsoft.com/en-us/research/project/machine-learning-edge/)
## Research Opportunities
### Model compression and optimization for specific hardware
#### General approaches for compression and optimization
1. Reduce the complexity of inputs.
2. Pre-computations on independent workload.
3. Share architectures with many CV tasks.
4. Cache in video processing.
#### Paper
[1] [Han et al. MCDNN: An approximation-based execution framework for deep stream processing under resource constraints. MobiSys'16.](https://homes.cs.washington.edu/~arvind/papers/mcdnn.pdf)<br>
[2] [Huynh et al. DeepMon: Mobile GPU-based Deep Learning Framework for Continuous Vision Applications. MobiSys'17.](https://nsr.cse.buffalo.edu/mobisys_2017/papers/pdfs/mobisys17-paper07.pdf)<br>
[3] [Xu et al. DeepCache: Principled Cache for Mobile Deep Vision. MobiCom'18.](https://arxiv.org/pdf/1712.01670.pdf)
### Optimization on heterogeneous hardware
[1] [Liu et al. On-Demand Deep Model Compression for Mobile Devices: A Usage-Driven Model Selection Framework. MobiSys'18.](https://tik-old.ee.ethz.ch/file//79a7dd6f6370f809e6180c0746232283/mobisys18-liu.pdf)<br>
[2] [Fany et al. NestDNN: Resource-Aware Multi-Tenant On-Device Deep Learning for Continuous Mobile Vision. MobiCom'18.](https://arxiv.org/abs/1810.10090)<br>
[3] [Cao et al. Efficient and Effective Sparse LSTM on FPGA with Bank-Balanced Sparsity. FPGA'19.](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/FPGA2019_final.pdf)<br>
[4] [Cao et al. SeerNet: Predicting Convolutional Neural Network Feature-Map Sparsity through Low-Bit Quantization. CVPR'19.](http://openaccess.thecvf.com/content_CVPR_2019/papers/Cao_SeerNet_Predicting_Convolutional_Neural_Network_Feature-Map_Sparsity_Through_Low-Bit_Quantization_CVPR_2019_paper.pdf)<br>
[5] [Lee et al. MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors. MobiCom'19.](https://arxiv.org/pdf/1908.07985.pdf)<br>
### Privacy and security (models and data)
[1] [Lee et al. Occlumency: Privacy-preserving Remote Deep-learning Inference Using SGX. MobiCom'19.](http://soar.group/pubs/Occlumency.MobiCom19.pdf)
### Continual and collaborative learning
[1] [Lu et al. Collaborative Learning between Cloud and End Devices: An Empirical Study on Location Prediction. SEC'19.](https://www.microsoft.com/en-us/research/publication/collaborative-learning-between-cloud-and-end-devices-an-empirical-study-on-location-prediction/)
## Applications
[1] [Zeng et al. MobileDeepPill: A Small-Footprint Mobile Deep Learning System for Recognizing Unconstrained Pill Images. MobiSys'17.](https://www.egr.msu.edu/~mizhang/papers/2017_MobiSys_MobileDeepPill.pdf)<br>
[2] [Cao et al. DeQA: On-Device Question Answering. MobiSys'19.](https://awk.ai/assets/deqa.pdf)<br>

