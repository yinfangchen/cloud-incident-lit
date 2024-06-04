# Cloud Incident Literature
Cloud (including microservices) incidents/failures related work.


## Study
- How to Fight Production Incidents? An Empirical Study on a Large-scale Cloud Service. Supriyo Ghosh, et al. SoCC'22 [paper](https://dl.acm.org/doi/pdf/10.1145/3542929.3563482)
- Characterizing Microservice Dependency and Performance: Alibaba Trace Analysis. Shutian Luo, et al. SoCC'21 [paper](https://dl.acm.org/doi/10.1145/3472883.3487003)
- What Can We Learn from Four Years of Data Center Hardware Failures? Guosai Wang et al. DSN'17 [paper](https://people.iiis.tsinghua.edu.cn/~weixu/Krvdro9c/dsn17-wang.pdf)

## Benchmarks
- An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud & Edge Systems. Yu Gan, et al. ASPLOS'19 [paper](https://gy1005.github.io/publication/2019.asplos.deathstarbench/2019.asplos.deathstarbench.pdf)
- Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study. Xiang Zhou, et al. IEEE Transactions on SE'18 [paper](https://ieeexplore.ieee.org/document/8580420)
- µSuite: A Benchmark Suite for Microservices. Akshitha Sriraman, et al. IISWC'18 [paper](https://akshithasriraman.eecs.umich.edu/pubs/IISWC2018-%CE%BCSuite-preprint.pdf)
  
## Monitoring & Tracing
- Graph-Based Trace Analysis for Microservice Architecture Understanding and Problem Diagnosis. Xiaofeng Guo, et al. ESEC/FSE'20 [paper](https://dl.acm.org/doi/pdf/10.1145/3368089.3417066) 
- CloudSeer: Workflow Monitoring of Cloud Infrastructures via Interleaved Logs. Xiao Yu, et al. ASPLOS'16 [paper](https://dl.acm.org/doi/10.1145/2872362.2872407)
- Pivot Tracing: Dynamic Causal Monitoring for Distributed Systems. Jonathan Mace, et al. SOSP'15 [paper](https://dl.acm.org/doi/10.1145/2815400.2815415)
- The Mystery Machine: End-to-end Performance Analysis of Large-scale Internet Services. Michael Chow, et al. OSDI'14 [paper](https://dl.acm.org/doi/10.1145/2872362.2872407)
- Dapper, a Large-Scale Distributed Systems Tracing Infrastructure. Benjamin H. Sigelman, et al. Technical report'10 [paper](https://static.googleusercontent.com/media/research.google.com/en//archive/papers/dapper-2010-1.pdf)
- X-Trace: A Pervasive Network Tracing Framework. Rodrigo Fonseca, et al. NSDI'07 [paper](https://www.usenix.org/legacy/event/nsdi07/tech/full_papers/fonseca/fonseca.pdf)


## Detection & Triage
- (AnoFusion) Robust Multimodal Failure Detection for Microservice Systems. Chenyu Zhao, el al. KDD'23 [paper](https://arxiv.org/pdf/2305.18985)
- (MSTGAD) Twin Graph-based Anomaly Detection via Attentive Multi-Modal Learning for Microservice System. Jun Huang, et al. ASE'23 [paper](https://arxiv.org/pdf/2310.04701)
- Deeptralog: Trace-log combined microservice anomaly detection through graph-based deep learning. Chenxi Zhang, et al. ICSE'22 [paper](https://cspengxin.github.io/publications/icse22-DeepTraLog.pdf) 
- Fighting the Fog of War: Automated Incident Detection for Cloud Systems. Liqun Li, et al. ATC'21 [paper](https://www.usenix.org/system/files/atc21-li-liqun.pdf)
- FIRM: An Intelligent Fine-Grained Resource Management Frameworkfor SLO-Oriented Microservices. Haoran Qiu, et al. OSDI'20 [paper](https://dl.acm.org/doi/pdf/10.5555/3488766.3488812)
- Unsupervised Detection of Microservice Trace Anomalies through Service-Level Deep Bayesian Networks. Ping Liu, et al. ISSRE'20 [paper](https://netman.aiops.org/wp-content/uploads/2020/09/%E5%88%98%E5%B9%B3issre.pdf)
- Continuous Incident Triage for Large-Scale Online Service Systems. Junjie Chen, et al. ASE'19 [paper](http://hongyujohn.github.io/ASE19b.pdf)
- An Empirical Investigation of Incident Triage for Online Service Systems. Junjie Chen, et al. ICSE-SEIP'19 [paper](https://netman.aiops.org/~peidan/ANM2021/12.IncidentManagement/LectureCoverage/2019ICSE_An%20Empirical%20Investigation%20of%20Incident%20Triage%20for%20Online%20Service%20Systems.pdf)


## Root Causing
- (RCACopilot) Automatic Root Cause Analysis via Large Language Models for Cloud Incidents. Yinfang Chen, et al. EuroSys'24 [paper](https://yinfangchen.github.io/assets/pdf/rcacopilot_paper.pdf)
- GAMMA: Graph Neural Network-Based Multi-Bottleneck Localization for Microservices Applications. Gagan Somashekar, et al. WWW'24 [paper](https://www3.cs.stonybrook.edu/~anshul/www24_gamma.pdf)
- Nezha: Interpretable Fine-Grained Root Causes Analysis for Microservices on Multi-Modal Observability Data. Guangba Yu, et al. FSE'23 [paper](https://github.com/IntelligentDDS/Nezha/blob/main/FSE2023_Nezha.pdf)
- Eadro: An End-to-End Troubleshooting Framework for Microservices on Multi-source Data. Cheryl Lee, et al. ICSE'23 [paper](https://arxiv.org/pdf/2302.05092)
- (DiagFusion) Robust Failure Diagnosis of Microservice System through Multimodal Data. Shenglin Zhang, et al. arXiv'23 [paper](https://arxiv.org/pdf/2302.10512.pdf)
- Recommending Root-Cause and Mitigation Steps for Cloud Incidents using Large Language Models. Toufique Ahmed, et al. ICSE'23 [paper](https://arxiv.org/pdf/2301.03797.pdf)
- Mining Root Cause Knowledge from Cloud Service Incident Investigations for AIOps. Amrita Saha, et al. arXiv'22 [paper](https://arxiv.org/pdf/2204.11598.pdf)
- Sage: Practical & Scalable ML-Driven Performance Debugging in Microservices. Yu Gan, et al. ASPLOS'21 [paper](https://gy1005.github.io/publication/2021.asplos.sage/2021.asplos.sage.pdf)
- Groot: An event-graph-based approach for root cause analysis in industrial settings. Hanzhang Wang, et al. ASE'21 [paper](https://dl.acm.org/doi/abs/10.1109/ASE51524.2021.9678708)
- Practical Root Cause Localization for Microservice Systems via Trace Analysis. Zeyan Li, et al. IWQOS'21 [paper](https://netman.aiops.org/wp-content/uploads/2021/05/1570705191.pdf)
- CloudRCA: A Root Cause Analysis Framework for Cloud Computing Platforms. Yingying Zhang, et al. CIKM'21 [paper](https://arxiv.org/pdf/2111.03753.pdf)
- MicroHECL: high-efficient root cause localization in large-scale microservice systems. Dewei Liu, et al. ICSE-SEIP'21 [paper](https://dl.acm.org/doi/10.1109/ICSE-SEIP52600.2021.00043)
- Predicting Node Failures in an Ultra-large-scale Cloud Computing Platform: an AIOps Solution. Yangguang Li, et al. ACM Transactions on Software Engineering and Methodology'20 [paper](https://www.hengli.org/pdf/Li2020NodeFailurePrediction.pdf)
- Seer: Leveraging Big Data to Navigate the Complexity of Performance Debugging in Cloud Microservices. Yu Gan, et al. ASPLOS'19 [paper](https://www.csl.cornell.edu/~delimitrou/papers/2019.asplos.seer.pdf)
- Latent error prediction and fault localization for microservice applications by learning from system trace logs. Xiang Zhou, et al. ESEC/FSE'19 [paper](https://dl.acm.org/doi/10.1145/3338906.3338961)
- Automated known problem diagnosis with event traces. Chun Yuan, et al. EuroSys'06 [paper](https://dl.acm.org/doi/10.1145/1217935.1217972)
- Delta Debugging Microservice Systems. Xiang Zhou, et al. ASE'18 [paper](https://cspengxin.github.io/publications/ase18-debugmicroservice.pdf)


## Mitigation
- How to Mitigate the Incident? An Effective Troubleshooting Guide Recommendation Technique for Online Service Systems. Jiajun Jiang, et al. FSE'20 [paper](https://xgdsmileboy.github.io/files/paper/deeprmd-fse20.pdf)
- AutoTSG: Learning and Synthesis for Incident Troubleshooting. Manish Shetty, et al. arXiv'22 [paper](https://arxiv.org/pdf/2205.13457.pdf)

## Fault Injection for Cloud
- MicroFI: Non-Intrusive and Prioritized Request-Level Fault Injection for Microservice Applications. Hongyang Chen, et al. [paper](https://yuxiaoba.github.io/publication/microfi24/microfi24.pdf)

<!-- ## Learning-based
### Literature
- Effective Bug Triage Based on Historical Bug-Fix Information
 -->
