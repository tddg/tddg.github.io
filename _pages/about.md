---
layout: about
title: about
permalink: /
subtitle: Associate Professor at the University of Virginia

profile:
  align: right
  image: YueCheng.png
  image_cicular: 
  address: >
    <!--p><a href="mailto:mrz7dp@virginia.edu"><i class="fas fa-envelope"></i> mrz7dp _AT_ virginia.edu</a></p-->
    <p><i class="fas fa-envelope"></i> mrz7dp _AT_ virginia.edu</p>
    <p>SDS,CS@UVA </p>
    <p>Data Systems Researcher</p>

news: 2
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am an Associate Professor of [Data Science](https://datascience.virginia.edu/){:target="\_blank"} 
and [Computer Science](https://engineering.virginia.edu/departments/computer-science){:target="\_blank"} at
the [University of Virginia](https://www.virginia.edu/){:target="\_blank"}. 
My research covers a range of topics including distributed systems,
serverless and cloud computing, storage systems, operating systems,
and high-performance computing. 
My current research focuses on designing scalable, high-performance, and
easy-to-use computer **systems** that manage and process huge volume of
**data**.

Currently I am working on: 
(1) **Serverless and FaaS:** improving serverless computing using a
end-to-end approach that cuts across the entire software-hardware
stack: *(stateful) applications, middleware, platforms, and
lower-level OS/HW*; 
(2) **Data Reduction:** rethinking data reduction techniques for
large data-intensive applications;
(3) **Sys4ML:** building better (computing and storage) systems for
(distributed) ML applications; 
and (4) **ML4Sys:** improving systems software and infrastructure
management by using learned or data-driven approaches.

I am the recipient of an 
[NSF CAREER Award](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2045680&HistoricalAwards=false){:target="\_blank"} (2021), 
an Amazon Research Award (2021), 
a [Meta Research Award](https://research.facebook.com/blog/2022/9/announcing-the-winners-of-the-2022-ai-system-hardwaresoftware-codesign-request-for-proposals/?locale=en_US&draft=1284382378973290){:target="\_blank"} (2022),
[the IEEE CS TCHPC Early Career Researchers Award for Excellence
in HPC](https://tc.computer.org/tchpc/2022/10/06/2022-ieee-cs-tchpc-award-winners/){:target="\_blank"} (2022), 
and a [Samsung GRO 2023 Award](https://www.sait.samsung.co.kr/saithome/about/collabo_recipients.do){:target="\_blank"} (2023).
Prior to joining UVA, I was an Assistant Professor of 
[Computer Science](https://cs.gmu.edu/){:target="\_blank"} at 
[George Mason University](https://www.gmu.edu/){:target="\_blank"}, from 2017 to 2022.
I received my Ph.D. degree in [Computer Science](https://cs.vt.edu/){:target="\_blank"} from
[Virginia Tech](https://vt.edu/){:target="\_blank"}, working with Dr.
[Ali R. Butt](https://people.cs.vt.edu/butta/){:target="\_blank"}. 
During my Ph.D. I spent two summers at IBM Research Almaden in 2013
and 2014, and six months at Dell EMC Princeton Office in 2015. 


## selected projects

Most of my projects are open-source and available on our group's [GitHub page](https://github.com/ds2-lab){:target="\_blank"}.


* **InfiniStore:** Storing large and small objects on a dynamic fleet of serverless functions with only 3% of ElastiCache's cost but without sacrificing performance and availability.  
  [[ASPLOS'23](https://tddg.github.io/assets/pdf/asplos23-lambdafs-ae.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/LambdaFS){:target="\_blank"}] -- 
  [[VLDB'23](https://tddg.github.io/assets/pdf/vldb23-infinistore.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/infinistore){:target="\_blank"}] --
  [[FAST'20](https://www.usenix.org/conference/fast20/presentation/wang-ao){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/infinicache){:target="\_blank"}]

* **Wukong:** Scaling out Python parallel programs (e.g., Dask applications) on FaaS without worrying about tedious cluster management. Wukong uses a new decentralized scheduling technique, which decentralizes resource orchestration to each individual serverless function, thereby enabling high elasticity and high scalability.  
  [[SoCC'20](https://tddg.github.io/assets/pdf/socc20-wukong.pdf){:target="\_blank"}] 
  [[PDSW'19](https://arxiv.org/abs/1910.05896){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/Wukong){:target="\_blank"}]

* **FaaSNet:** A highly scalable container provisioning framework that can provision thousands of 10+GB serverless function containers with just a few seconds. FaaSNet is currently deployed at [Alibaba Function Compute](https://www.alibabacloud.com/product/function-compute){:target="\_blank"}.  
  [[ATC'21](https://www.usenix.org/conference/atc21/presentation/wang-ao){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/FaaSNet){:target="\_target"}] [[Alibaba Cloud Blog](https://www.alibabacloud.com/blog/597937){:target="\_blank"}]
  
* **SFS:** Linux CFS is not ideal for short-lived serverless function workloads. SFS instead optimizes the turnaround time for transient function jobs.  
  [[SC'22](https://arxiv.org/abs/2209.01709){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/SFS){:target="\_blank"}] 

* **SHADE:** A common practice in deep learning training is to randomly shuffle all training samples epoch by epoch. With SHADE, you can cache the most important training samples without losing training quality.  
  [[FAST'23](https://www.usenix.org/conference/fast23/presentation/khan)]: [[GitHub](https://github.com/R-I-S-Khan/SHADE){:target="\_blank"}] 

* **DIGEST:** Scaling GNN training using a disaggregated storage.  
  [[arXiv](https://arxiv.org/abs/2206.00057){:target="\_blank"}]: [[code](#)]


