# Cloud Incident Literature
Cloud (including microservices) incidents/failures related work.


## Study
- How to Fight Production Incidents? An Empirical Study on a Large-scale Cloud Service. Supriyo Ghosh, et al. SoCC'22 [paper](https://dl.acm.org/doi/pdf/10.1145/3542929.3563482)
- Characterizing Microservice Dependency and Performance: Alibaba Trace Analysis. Shutian Luo, et al. SoCC'21 [paper](https://dl.acm.org/doi/10.1145/3472883.3487003)
- What Can We Learn from Four Years of Data Center Hardware Failures? Guosai Wang et al. DSN'17 [paper](https://people.iiis.tsinghua.edu.cn/~weixu/Krvdro9c/dsn17-wang.pdf)
- A Survey on Failure Analysis and Fault Injection in AI Systems. Guangba Yu, et al. [paper](https://arxiv.org/pdf/2407.00125)
- Why Does the Cloud Stop Computing? Lessons from Hundreds of Service Outages. Haryadi S. Gunawi, et al. SoCC'16 [paper](https://ucare.cs.uchicago.edu/pdf/socc16-cos.pdf)
- What Bugs Live in the Cloud? A Study of 3000+ Issues in Cloud Systems. Haryadi S. Gunawi, et al. SoCC'14 [paper](https://ucare.cs.uchicago.edu/pdf/socc14-cbs.pdf)

## Benchmarks
- Blueprint: A Toolchain for Highly-Reconfigurable Microservice Applications. Vaastav Anand, et al. SOSP'23 [paper](https://blueprint-uservices.github.io/assets/pdf/anand2023blueprint.pdf)
- (DeathStarBench) An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud & Edge Systems. Yu Gan, et al. ASPLOS'19 [paper](https://gy1005.github.io/publication/2019.asplos.deathstarbench/2019.asplos.deathstarbench.pdf)
- (TrainTicket) Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study. Xiang Zhou, et al. IEEE Transactions on SE'18 [paper](https://ieeexplore.ieee.org/document/8580420)
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
<!-- - ChangeRCA: Finding Root Causes from Software Changes in Large Online Systems. Guangba Yu, et al. FSE'24 [paper](https://dl.acm.org/doi/10.1145/3643728)  -->
<!-- - BARO: Robust Root Cause Analysis for Microservices via Multivariate Bayesian Online Change Point Detection. Luan Pham, et al. FSE'24 [paper](https://dl.acm.org/doi/10.1145/3660805) -->
- A Quantitative and Qualitative Evaluation of LLM-Based Explainable Fault Localization. Sungmin Kang, et al. FSE'24 [paper](https://dl.acm.org/doi/10.1145/3660771) 
- Chain-of-Event: Interpretable Root Cause Analysis for Microservices through Automatically Learning Weighted Event Causal Graph. Zhenhe Yao, et al. FSE'24 [paper](https://dl.acm.org/doi/10.1145/3663529.3663827) 
<!-- - Towards Better Graph Neural Network-Based Fault Localization through Enhanced Code Representation. Md Nakhla Rafi, et al. FSE'24 [paper](https://dl.acm.org/doi/10.1145/3660793) -->
<!-- - Illuminating the Gray Zone: Non-intrusive Gray Failure Localization in Server Operating Systems. Shenglin Zhang, et al. FSE'24 [paper](https://dl.acm.org/doi/pdf/10.1145/3663529.3663834)   -->
- Fault Diagnosis for Test Alarms in Microservices through Multi-source Data. Shenglin Zhang, et al. FSE(Industry)'24 [paper](https://dl.acm.org/doi/10.1145/3663529.3663833)
- Exploring LLM-based Agents for Root Cause Analysis. Devjeet Roy, et al. arXiv'24 [paper](https://arxiv.org/pdf/2403.04123)
- RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models. Zefan Wang, et al. arXiv'23 [paper](https://arxiv.org/pdf/2310.16340)
<!-- - PACE-LM: Prompting and Augmentation for Calibrated Confidence Estimation with GPT-4 in Cloud Incident Root Cause Analysis. Shizhuo Dylan Zhang, et al. FSE(Industry)'24 [paper](https://arxiv.org/pdf/2309.05833) -->
- Assess and summarize: Improve outage understanding with large language models. Pengxiang Jin, et al. arXiv'23 [paper](https://arxiv.org/pdf/2305.18084)
- Nezha: Interpretable Fine-Grained Root Causes Analysis for Microservices on Multi-Modal Observability Data. Guangba Yu, et al. FSE'23 [paper](https://github.com/IntelligentDDS/Nezha/blob/main/FSE2023_Nezha.pdf)
- Eadro: An End-to-End Troubleshooting Framework for Microservices on Multi-source Data. Cheryl Lee, et al. ICSE'23 [paper](https://arxiv.org/pdf/2302.05092)
- (DiagFusion) Robust Failure Diagnosis of Microservice System through Multimodal Data. Shenglin Zhang, et al. arXiv'23 [paper](https://arxiv.org/pdf/2302.10512.pdf)
- Recommending Root-Cause and Mitigation Steps for Cloud Incidents using Large Language Models. Toufique Ahmed, et al. ICSE'23 [paper](https://arxiv.org/pdf/2301.03797.pdf)
- Mining Root Cause Knowledge from Cloud Service Incident Investigations for AIOps. Amrita Saha, et al. arXiv'22 [paper](https://arxiv.org/pdf/2204.11598.pdf)
- Scalable Statistical Root Cause Analysis on App Telemetry. Vijayaraghavan Murali, et al. ICSE-SEIP'21 [paper](https://arxiv.org/pdf/2010.09974) 
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
- MicroFI: Non-Intrusive and Prioritized Request-Level Fault Injection for Microservice Applications. Hongyang Chen, et al. TDSC'24 [paper](https://ieeexplore.ieee.org/document/10428037)
- Chronos: Finding Timeout Bugs in Practical Distributed Systems by Deep-Priority Fuzzing with Transient Delay. Yuanliang Chen, et al. S&P'24 [paper](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/Chronos_sp24.pdf) [code](https://github.com/SecTechTool/Chronos)
- Acto: Automatic End-to-End Testing for Operation Correctness of Cloud System Management. Jiawei Tyler Gu, et al. SOSP'23 [paper](https://www.cs.cornell.edu/~legunsen/pubs/GuETAlActoSOSP23.pdf) [code](https://github.com/xlab-uiuc/acto)
- Phoenix: Detect and Locate Resilience Issues in Blockchain via Context-Sensitive Chaos. Fuchen Ma, et al. CCS'23 [paper](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/CCS23.pdf)
- Coverage Guided Fault Injection for Cloud Systems. Yu Gao, et al. ICSE'23 [paper](http://www.tcse.cn/~gaoyu15/paper/2023-icse-crashfuzz.pdf) [code](https://github.com/tcseiscas/crashfuzz)
- Push-Button Reliability Testing for Cloud-Backed Applications with Rainmaker. Yinfang Chen, et al. NSDI'23 [paper](https://www.usenix.org/system/files/nsdi23-chen-yinfang.pdf) [code](https://github.com/xlab-uiuc/rainmaker)
- Fail through the Cracks: Cross-System Interaction Failures in Modern Cloud Systems. Lilia Tang, et al. Eurosys'23 [paper](https://tianyin.github.io/pub/csi-failures.pdf) [[code]](https://github.com/xlab-uiuc/csi-ae)
- Automatic Reliability Testing for Cluster Management Controllers. Xudong Sun et al. OSDI'22 [paper](https://www.usenix.org/conference/osdi22/presentation/sun) [code](https://github.com/sieve-project/sieve)
- IBIR: Bug Report driven Fault Injection. Ahmed Khanfir et al. FSE'22 [paper](https://arxiv.org/pdf/2012.06506.pdf) [code](https://github.com/serval-uni-lu/IBIR)
- SlowCoach Mutating Code to Simulate Performance Bugs. Yiqun Chen, et al. ISSRE'22 [paper](https://ssg.lancs.ac.uk/wp-content/uploads/yq-slowcoach.pdf) 
<!-- - Towards a Fault Taxonomy for Microservices-Based Applications. SBES'22 [paper](https://dl.acm.org/doi/fullHtml/10.1145/3555228.3555245) -->
- Understanding a Program’s Resiliency Through Error Propagation. Zhimin Li, et al. PPoPP'21 [paper](https://dl.acm.org/doi/pdf/10.1145/3437801.3441589)
- CoFI: Consistency-Guided Fault Injection for Cloud Systems. Haicheng Chen, et al. ASE'20 [paper](https://dl.acm.org/doi/pdf/10.1145/3324884.3416548) [code](https://hanseychen.github.io/CoFI/)
- How Far Have We Come in Detecting Anomalies in Distributed Systems? An Empirical Study with a Statement-level Fault Injection Method. Yong Yang, et al. ISSRE'20 [paper](https://ieeexplore.ieee.org/document/9251065)
- ProFIPy: Programmable Software Fault Injection as-a-Service. Roberto Natella, et al. DSN'20 [paper](https://dl.acm.org/doi/10.1145/2841425)
- Fitness-guided Resilience Testing of Microservice-based Applications. Zhenyue Long, et al. ICWS'20 [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9283918)
- Co-evolving Tracing and Fault Injection with Box of Pain. Daniel Bittman, et al. HotCloud'19 [paper](https://www.usenix.org/system/files/hotcloud19-paper-bittman.pdf)
- Automating Failure Testing Research at Internet Scale. Peter Alvaro, et al. SoCC'16 [paper](https://dl.acm.org/doi/10.1145/2987550.2987555)

<!-- - 19_Chaos_TRIPLE AGENT- Monitoring, Perturbation and  Failure-obliviousness for Automated Resilience Improvement in Java Applications [paper](https://arxiv.org/abs/1812.10706)
- 18_Chaos_A Program-Aware Fault-Injection Method for Dependability Evaluation Against Soft-Error Using Genetic Algorithm [paper](https://www.worldscientific.com/doi/10.1142/S021812661850144X)
- 18_TDSC_Faultprog: Testing the Accuracy of Binary-Level Software Fault Injection [paper](https://ieeexplore.ieee.org/document/7394118/)
- 16_Survey_Assessing Dependability with Software Fault Injection: A Survey [paper](https://dl.acm.org/doi/10.1145/2841425)
- 15_SIGMOD_Lineage-driven Fault Injection [paper](https://dl.acm.org/doi/10.1145/2723372.2723711)
-->

<!-- ## Learning-based
### Literature
- Effective Bug Triage Based on Historical Bug-Fix Information
 -->
