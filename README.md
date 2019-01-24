# papers-notebook-with-scheduling

## 論文文獻筆記

此專案記錄自己閱讀論文彙整，並透過閱讀過程記錄研究方法與重點，其整理分類幫助自己正確朝著題目方向深入探討。

### Keywords:
- AS: Auto Scaling
- DL: Deep Learning
- DS: Distributed system
- NE: Network efficient
- RM: Resource management
- RU: Resource Utilization
- RS: Resource scheduling
- DMLCS: Distributed machine learning Centralized scheduling

## 文獻
### 排程 Scheduler 
| Keywords | Paper Title| PDF | Slide | Year |
| ------ | ----------- | ----------- | ----------- |---|
| DL, AS, kubernetes| Deep Learning Based Auto-Scaling Load Balancing Mechanism for Distributed Software-Defined Storage Service |  [[pdf]](https://ndltd.ncl.edu.tw/cgi-bin/gs32/gsweb.cgi/login?o=dnclcdr&s=id=%22106NTTI5392012%22.&searchmode=basic) | [slide]| 2018|
| DL, DS | GeePS: Scalable deep learning on distributed GPUs with a GPU-specialized parameter server |  [[pdf]](http://www.pdl.cmu.edu/PDL-FTP/CloudComputing/GeePS-cui-eurosys16.pdf) | [[slide]](https://www.cs.cmu.edu/~hzhang2/projects/GeePS/slides.pdf)| 2015|
| DL, DS| Multi-tenant GPU Clusters for Deep Learning Workloads: Analysis and Implications |  [[pdf]](https://www.microsoft.com/en-us/research/uploads/prod/2018/05/gpu_sched_tr.pdf) | [slide]| 2018|
| DL, Scheduling| Online Job Scheduling in Distributed Machine Learning Clusters |  [[pdf]](https://arxiv.org/pdf/1801.00936.pdf) | [[slide]]| 2018|
| DL, Scheduling| Gandiva: Introspective Cluster Scheduling for Deep Learning |  [[pdf]](https://www.usenix.org/system/files/osdi18-xiao.pdf) | [slide](https://www.usenix.org/sites/default/files/conference/protected-files/osdi18_slides_sivathanu.pdf)| 2018|
| DL, Scheduling | Scheduling CPU for GPU-based Deep Learning Jobs |  [[pdf]](https://goo.gl/UQ99sG ) | [slide]| 2018|
| NE, DL,Scheduling| DLTAP: A Network-efficient Scheduling Method for Distributed Deep Learning Workload in Containerized Cluster Environment |  [[pdf]](https://www.itm-conferences.org/articles/itmconf/pdf/2017/04/itmconf_ita2017_03030.pdf) | [[slide]]| 2018|
| RM, DMLCS,RU | GAI: A Centralized Tree-Based Scheduler for Machine Learning Workload in Large Shared Clusters |  [[pdf]](https://link.springer.com/content/pdf/10.1007%2F978-3-030-05054-2_46.pdf) | [slide]| 2018|
| RM | Optimus: An Efficient Dynamic Resource Scheduler for Deep Learning Cluster |  [[pdf]](https://arxiv.org/pdf/1512.06216.pdf ) | [slide]]| 2018|
| DS,PS | Scaling Distributed Machine Learning with the Parameter Server |  [[pdf]](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-li_mu.pdf ) | [[slide]](https://www.usenix.org/sites/default/files/conference/protected-files/osdi14_slides_li-mu.pdf)[[Video]](https://www.usenix.org/node/186215)| 2014|
| DL,Training System | Project Adam: Building an Efficient and Scalable Deep Learning Training System |  [[pdf]](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-chilimbi.pdf ) | [[Video]](https://www.usenix.org/node/186213)| 2014|
| DL, PS |Parameter Hub: a Rack-Scale Parameter Server for Distributed Deep Neural Network Training | [[pdf]](https://arxiv.org/pdf/1805.07891.pdf) | [slide]]| 2018|
| DL, PS |Scaling Distributed Machine Learning with the Parameter Server | [[pdf]](https://www.cs.cmu.edu/~muli/file/parameter_server_osdi14.pdf) | [slide]]| 2014|
| ML, Datacenter |Applied Machine Learning at Facebook:A Datacenter Infrastructure Perspective | [[pdf]](https://research.fb.com/wp-content/uploads/2017/12/hpca-2018-facebook.pdf) | [slide]]| 2014|
| ML,  benchmarking |Kubebench: A Benchmarking Platform for ML Workloads | [[pdf]](https://alln-extcloud-storage.cisco.com/ciscoblogs/5c0fda3a560b9.pdf) | [slide]]| 2018|
| Scheduling, GPU, Workload | Topology-Aware GPU Scheduling for Learning Workloads in Cloud Environments | [[pdf]](https://upcommons.upc.edu/bitstream/handle/2117/114851/Topology-Aware%20GPU%20Scheduling%20for%20Learning%20Workloads.pdf) | [slide]]| 2017|



---
### Classic [排程(Scheduler)]
- [Comparison of Container Schedulers](https://medium.com/@ArmandGrillet/comparison-of-container-schedulers-c427f4f7421)
- [The evolution of cluster scheduler architectures[翻譯]](http://dockone.io/article/1113)
- [TensorFlow: A system for large-scale machine learning](https://arxiv.org/pdf/1605.08695.pdf)

### Paper Direction
- Traditional scheduling architecture
- Machine learning Distributed Cluster 
    - Model training
    - Farmwork
    - Parameters Server / AllReduce
- Combination of both
