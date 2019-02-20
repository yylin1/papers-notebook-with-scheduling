# papers-notebook-with-scheduling

## 論文文獻筆記

此專案記錄閱讀論文彙整，並透過閱讀過程記錄研究方法與重點，其整理`Papers`分類幫助自己正確朝著研究方向深入探討。


### Keywords Shortcuts:
- AS: Auto Scaling
- DL: Deep Learning
- DS: Distributed system
- NE: Network efficient
- RM: Resource management
- RU: Resource Utilization
- RC: Resource Contention
- RS: Resource scheduling
- DMLCS: Distributed machine learning Centralized scheduling
- PA: Performance Analysis
- PT: Parallelized Training

## 文獻
### 排程 Scheduler

| Keywords | Paper Title| PDF | Slide | Year |
| ------ | ----------- | ----------- | ----------- |---|
| DL, Scheduling| Gandiva: Introspective Cluster Scheduling for Deep Learning |  [[pdf]](https://www.usenix.org/system/files/osdi18-xiao.pdf) | [[slide]](https://www.usenix.org/sites/default/files/conference/protected-files/osdi18_slides_sivathanu.pdf)| 2018|
| DL, CPU, RS | **Scheduling CPU for GPU-based Deep Learning Jobs** |  [[pdf]](https://goo.gl/UQ99sG ) | [slide]| 2018|
| DL, NE, Scheduling| DLTAP: A Network-efficient Scheduling Method for Distributed Deep Learning Workload in Containerized Cluster Environment |  [[pdf]](https://www.itm-conferences.org/articles/itmconf/pdf/2017/04/itmconf_ita2017_03030.pdf) | [slide]| 2018|
| DL,Training System | Project Adam: Building an Efficient and Scalable Deep Learning Training System |  [[pdf]](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-chilimbi.pdf ) | [[Video]](https://www.usenix.org/node/186213)| 2014|
| DL, PS, Rack-Scale |Parameter Hub: a Rack-Scale Parameter Server for Distributed Deep Neural Network Training | [[pdf]](https://arxiv.org/pdf/1805.07891.pdf) | [slide]| 2018|
| ML, PS |Scaling Distributed Machine Learning with the Parameter Server | [[pdf]](https://www.cs.cmu.edu/~muli/file/parameter_server_osdi14.pdf) | [slide]| 2014|
| ML, Infra |Applied Machine Learning at Facebook:A Datacenter Infrastructure Perspective | [[pdf]](https://research.fb.com/wp-content/uploads/2017/12/hpca-2018-facebook.pdf) | [slide]| 2014|
| RM | Optimus: An Efficient Dynamic Resource Scheduler for Deep Learning Cluster |  [[pdf]](https://i.cs.hku.hk/~cwu/papers/yhpeng-eurosys18.pdf ) | [slide]| 2018|
| DS, PS | Scaling Distributed Machine Learning with the Parameter Server |  [[pdf]](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-li_mu.pdf ) | [[slide]](https://www.usenix.org/sites/default/files/conference/protected-files/osdi14_slides_li-mu.pdf)[[Video]](https://www.usenix.org/node/186215)| 2014|
| Scheduling, GPU, PA, RC | **Topology-Aware GPU Scheduling for Learning Workloads in Cloud Environments** | [[pdf]](https://upcommons.upc.edu/bitstream/handle/2117/114851/Topology-Aware%20GPU%20Scheduling%20for%20Learning%20Workloads.pdf) | [slide]| 2017|


#### # kubernetes 
| Keywords | Paper Title| PDF | Slide | Year |
| ------ | ----------- | ----------- | ----------- |---|
| DL, AS, kubernetes| **Deep Learning Based Auto-Scaling Load Balancing Mechanism for Distributed Software-Defined Storage Service** |  [[pdf]](https://ndltd.ncl.edu.tw/cgi-bin/gs32/gsweb.cgi/login?o=dnclcdr&s=id=%22106NTTI5392012%22.&searchmode=basic) | [slide]| 2018|
| ML, benchmarking, kubernetes |Kubebench: A Benchmarking Platform for ML Workloads | [[pdf]](https://alln-extcloud-storage.cisco.com/ciscoblogs/5c0fda3a560b9.pdf) | [slide]| 2018|
| RM, DMLCS,RU, kubernetes | GAI: A Centralized Tree-Based Scheduler for Machine Learning Workload in Large Shared Clusters |  [[pdf]](https://link.springer.com/content/pdf/10.1007%2F978-3-030-05054-2_46.pdf) | [slide]| 2018
| DL, Scheduling, Algorithm | **Online Job Scheduling in Distributed Machine Learning Clusters** |  [[pdf]](https://arxiv.org/pdf/1801.00936.pdf) | [slide]| 2018|
| Autoscaling, kubernetes | Containers Orchestration with Cost-Efficient Autoscaling in Cloud Computing Environments |  [[pdf]](https://arxiv.org/pdf/1812.00300.pdf) | [slide]| 2018|
| DL, PT, kubernetes | Parallelized Training of Deep NN – Comparison of Current Concepts and Frameworks |  [[pdf]](https://arxiv.org/pdf/1812.00300.pdf) | [slide]| 2018|
 

#### # other 

| Keywords | Paper Title| PDF | Slide | Year |
| ------ | ----------- | ----------- | ----------- |---|
| DL, DS| Multi-tenant GPU Clusters for Deep Learning Workloads: Analysis and Implications |  [[pdf]](https://www.microsoft.com/en-us/research/uploads/prod/2018/05/gpu_sched_tr.pdf) | [slide]| 2018|
| DL, DS | **GeePS: Scalable deep learning on distributed GPUs with a GPU-specialized parameter server** |  [[pdf]](http://www.pdl.cmu.edu/PDL-FTP/CloudComputing/GeePS-cui-eurosys16.pdf) | [[slide]](https://www.cs.cmu.edu/~hzhang2/projects/GeePS/slides.pdf)| 2015|
| DL | Poseidon: A system architecture for efficient GPU-based deep learning on multiple machines |  [[pdf]](https://arxiv.org/pdf/1512.06216.pdf) | [slide]| 2015|
| Mesos, Marathon, Ceph | Toward High-Availability Container as a Service on Mesos Cluster with Distributed Shared Volumes |  [[pdf]](https://ndltd.ncl.edu.tw/cgi-bin/gs32/gsweb.cgi/login?o=dnclcdr&s=id=%22105CHPI0392016%22.&searchmode=basic) | [slide]| 2015|

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

### Ref-Link
- [分佈式機器學習/ 深度學習論文整理](http://jcf94.com/2017/12/20/2017-12-20-distributeddl/)


## Learning Scheduler 
- Scheulder affinity
- Scheduler Policy
- Hardware GPU topology
- Kube-batch

### Operator Learning 
- [使用 operator 擴展kubernetes- 沃趣科技-袁琳峰](http://bucket.k8smeetup.com/%E4%BD%BF%E7%94%A8%20Operator%20%E6%9D%A5%E6%89%A9%E5%B1%95%20Kubernetes.pdf)
- [Write an Operator to handle CRD](https://speakerdeck.com/kairen/write-an-operator-to-handle-crd)
- [Extending Kubernetes: Create Controllers for Core and Custom Resources](https://medium.com/@trstringer/create-kubernetes-controllers-for-core-and-custom-resources-62fc35ad64a3?fbclid=IwAR32SpJB-fsDdK3hlQwrmxG54EE_x1bFP7THDYjyrjgTe_kz6y_2bZkmx0s)
- [第一次玩 operator-sdk 就上手](https://bestsamina.github.io/posts/2019-02-04-first-operator-sdk-helm/?fbclid=IwAR0LGrYqIZ5c8h02gI8ohiVpdJj_Ug8AGqcx8WRsmLV8ol-YjJeINpCQhOk)

