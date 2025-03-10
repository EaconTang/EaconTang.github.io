# eacontang.github.io

## 个人信息
- 基础属性：男、32岁、籍广东梅州、定居深圳
- 教育背景：中山大学-软件工程-本科（2015年毕业）
- 工作经验：>9年
- 目前就职：腾讯wxg-运营开发-T10
- 匹配岗位：运营开发/后台开发/k8s容器开发/云原生架构
- 联系方式：(邮箱)eacon-tang@foxmail.com、(微信)tyingk


## 技能自评
- 熟悉C++/Go/Python、linux、rpc框架和常用中间件，能主导完成中大型系统的设计和开发
- 熟悉CNCF云原生架构技术栈（docker/k8s/tracing/mesh等），有大规模集群上云的实战经验
- 熟悉信息安全的技术架构体系，主导负责过复杂业务的策略PaaS平台开发
- 熟悉监控、Devops原理，设计开发过大数据监控产品、调用链追踪、流水线等基础平台
- 自驱学习能力+无障碍的英文读写能力，善于通过研究开源项目和新技术达成业务目的


## 工作经历
- **2018年5月 ~ 至今**
  - 公司：腾讯
  - 职位：运营开发
  - 核心项目与职责：
    - [2024→至今]  微信安全系统开发(关键词、case查询、回溯系统等)：核心开发
    - [2021→2023] 策略研发PaaS平台：技术负责人（虚线带6人小团队）
    - [2020→2021] k8s容器平台建设：技术负责人（k8s开源协同PMC）
    - [2019→2020] 调用链监控系统：核心开发
    - [2018→2019] devops运营平台(流程编排、k8s)：核心开发


- **2016年6月 ~ 2018年4月**
  - 公司：广州优亿科技（200~300人）
  - 职位：Python开发
  - 核心项目与职责：
    - 大数据平台监控产品：技术负责人 + 核心开发
    - AIOps机器学习智能运维竞赛(2018国内首届)：领队

- **2015年7月 ~ 2016年4月**
  - 公司：Coremail(网易联营)（300~500人）
  - 职位：Java开发
  - 核心项目与职责：
    - 后台接口自动化框架：模块开发


## 重点项目简述

### 关键词服务
```
【项目简介】：对海量文本请求进行匹配和拦截，包括：关键词后台过滤服务、词库运营平台、种子互通等模块。
【项目难点】：字符串匹配、集群容量调度、词库管理
【技术栈】：c++、go、mysql、pulsar-mq、redis、AC自动机算法
【相关数据】：单机峰值100+w/min、集群节点200+个(约1.2w+核)；词库量级6000+w、单词库最大300+w
```

### 策略研发PaaS平台开发
```
【项目简介】：一站式WebIDE策略研发平台，负责内容安全的策略下发、离线回扫和业务运营。
【项目难点】：业务复杂度高
【技术栈】：python、go、trpc、mysql、zookeeper、redis、pulsar-mq
【相关数据】：业务接入2000+；离线回扫任务2000+/min；后台请求量峰值4+亿/min
```

### K8s容器平台
```
【项目简介】：基于k8s的TKE容器基础平台建设，负责私有集群从0到1搭建、业务上云改造和平台运营开发。
【项目难点】：整体落地方案、业务上云、弹性伸缩、集群容量管理、调度优化(性能&稳定性)
【技术栈】：go、docker、k8s、linux、underlay/overlay、云原生
【相关数据】：集群规模60w+核、8000+节点、1w+实例；成本节约20%左右
```

### 调用链监控系统
```
【项目简介】：基于jaeger二次开发的分布式调用链监控平台
【项目难点】：数据采样、限流控制(令牌桶)、指标计算
【技术栈】：go、etcd、opentracing、jaeger、kafka、flink-streaming、ElasticSearch
【相关数据】：接入服务8+个；数据量5+亿/天
```

### Devops运营平台
```
【项目简介】：自研的大规模集群服务运营平台，支持CI/CD、流程编排，支持使用k8s统一管理非容器服务
【项目难点】：任务调度&隔离&控制、插件化设计、k8s集群管理、CRI接口实现、CAS内容寻址存储
【技术栈】：go、etcd、docker、k8s
【相关数据】：流水线任务2000+次/天；k8s集群规模7000+节点、接入服务120+个、1.3w+个pod
```

### 大数据平台监控产品
```
【项目简介】：基于OpenTSDB自研的大数据监控产品
【项目难点】：agent数据采集框架、告警规则引擎、告警过滤(BloomFilter)、异常检测
【技术栈】：python、opentsdb、HBase、DSL、docker-compose、sklearn
【相关链接】：
- [Github开源社区](https://github.com/amas-eye/amas)
- [2018年-首届AIOps挑战赛](https://challenge.aiops.cn/home/competition/1484452272200032281)
```

## 其他
- 【绩效历史】2次5星，1次4星，无3星以下的低绩效
- 【技术文章】腾讯云原生：《信安运维基于 TKE 平台的容器技术实践》[https://mp.weixin.qq.com/s/FtmdiF4UcPGOOxOPlP_ukw](https://mp.weixin.qq.com/s/FtmdiF4UcPGOOxOPlP_ukw)
- 【技术演讲】Pycon2016-深圳场：《大数据监控告警系统实现》[https://zhuanlan.zhihu.com/p/27382099](https://zhuanlan.zhihu.com/p/27382099)
- 【社区】Github：[https://github.com/EaconTang](https://github.com/EaconTang)
- 【社区】知乎：[https://www.zhihu.com/people/yktang/posts](https://www.zhihu.com/people/yktang/posts)