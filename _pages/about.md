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
(1) **LLM systems:** making LLM applications elastic and scalable;
(2) **Serverless and FaaS:** improving serverless computing using a
end-to-end approach that cuts across the entire ecosystem 
stack: *(stateful) applications, middleware, platforms, and
low-level OS/HW*; 
(3) **Data Reduction:** rethinking data reduction techniques for
large ML platforms like Hugging Face.

I am the recipient of an 
[NSF CAREER Award](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2322860&HistoricalAwards=false){:target="\_blank"} (2021), 
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

Our recent focus is on:
1. Designing **first-gen Serverless AI platforms** for ***Large Language Model (LLM) applications***,
2. Rethinking **storage system design** in the era of ***Generative AI and LLMs***.

I'm looking for motivated ***graduate/undergrad interns*** interested
in conducting research in cutting-edge LLM systems areas
(serverless AI, LLM agents, storage for ML/AI models/datasets). Feel
free to drop me an email if you are interested!

For our most recent projects, check our latest [preprints and publication](https://tddg.github.io/publication/).

* **Serverless AI:** Interactive ML/AI workloads require elastic
access to heterogeneous compute resources (GPU, CPU). We explore
new serverless execution paradigms to enable efficient 
GPU utilization and scalable and elastic GPU management for LLM
fine-tuning and inference. **λScale**
accelerates serverless LLM deployments and inference using RDMA and
dynamic pipeline parallelism. **NotebookOS** implements on-demand
GPUs for Jupyter Notebook-based interactive training workloads.
**ZenFlow** accelerates LLM fine-tuning by prioritizing and
decoupling parameter updates across fast GPU and slow CPU,
minimizing GPU stalls while preserving accuracy. 
**MorphServe** enables flexible and elastic GPU memory scaling for
bursty LLM inference workloads via dynamic model layer quantization
and KVC resizing. 
  * [[λScale preprint](https://arxiv.org/abs/2502.09922){:target="\_blank"}] 
  * [[NotebookOS preprint](https://arxiv.org/abs/2503.20591){:target="\_blank"}] 
  * [[ZenFlow preprint](https://arxiv.org/abs/2505.12242){:target="\_blank"}] 
  * [[MorphServe preprint](https://arxiv.org/abs/2506.02006){:target="\_blank"}] 
 
* **Storage Systems for AI:** We are rethinking storage system design to sustain the exponential AI data explosion. **zLLM** and **BitX** are new lossless compressing algorithms that reduce the LLM storage footprint by 50%.  ELF (and ELVES) near-losslessly compress ML models to achieve effective model storage reduction. SHADE and FedCaSe automatically and intelligently cache the most important training samples without losing training quality.  
  * [[zLLM preprint](https://arxiv.org/abs/2505.06252){:target="\_blank"}]
  * [[VLDB'24](https://www.vldb.org/pvldb/vol17/p2036-su.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/ELF){:target="\_blank"}]
  * [[SoCC'24](https://tddg.github.io/assets/pdf/socc24-fedcase.pdf){:target="\_blank"}]: [[GitHub](https://github.com/rkhan055/FedCaSe){:target="\_blank"}]
  * [[FAST'23](https://www.usenix.org/conference/fast23/presentation/khan){:target="\_blank"}]: [[GitHub](https://github.com/R-I-S-Khan/SHADE){:target="\_blank"}] 

* **FaaS Platform Management:** We design innovative systems solutions to make FaaS truly elastic. A highly scalable container provisioning framework that can provision thousands of 10+GB serverless function containers with just a few seconds. **FaaSNet [ATC'21] and CIDRE [ASPLOS'25] are both deployed at** [Alibaba Function Compute](https://www.alibabacloud.com/product/function-compute){:target="\_blank"}.  
  * [[ASPLOS'25](https://tddg.github.io/assets/pdf/asplos25-cidre.pdf){:target="\_blank"}]: [[GitHub](https://github.com/nzc5ve/cidre_asplos25){:target="\_target"}]
  * [[ATC'21](https://www.usenix.org/conference/atc21/presentation/wang-ao){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/FaaSNet){:target="\_target"}] [[Alibaba Cloud Blog](https://www.alibabacloud.com/blog/597937){:target="\_blank"}] 

* **Serverless Cloud Storage:** Storing large and small objects on a dynamic fleet of serverless functions with only 3% of ElastiCache's cost but without sacrificing performance and availability.  
  * [[ASPLOS'23](https://tddg.github.io/assets/pdf/asplos23-lambdafs-ae.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/LambdaFS){:target="\_blank"}] 
  * [[VLDB'23](https://tddg.github.io/assets/pdf/vldb23-infinistore.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/infinistore){:target="\_blank"}] 
  * [[FAST'20](https://www.usenix.org/conference/fast20/presentation/wang-ao){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/infinicache){:target="\_blank"}]

* **Serverless Parallel Computing:** Scaling out Python parallel programs (e.g., Dask applications) on FaaS without worrying about tedious cluster management. Wukong uses a new decentralized scheduling technique, which decentralizes resource orchestration to each individual serverless function, thereby enabling high elasticity and high scalability.  
  * [[SoCC'20](https://tddg.github.io/assets/pdf/socc20-wukong.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/Wukong){:target="\_blank"}]
  * [[PDSW'19](https://arxiv.org/abs/1910.05896){:target="\_blank"}]
  
* **Serverless Function OS Scheduling:** Linux CFS is not ideal for
short-lived serverless function workloads. This project rethinks OS
scheduling to minimize function turnaround time.  
  * [[ATC'24](https://tddg.github.io/assets/pdf/atc24-alps-ae.pdf){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/ALPS){:target="\_blank"}]
  * [[SC'22](https://arxiv.org/abs/2209.01709){:target="\_blank"}]: [[GitHub](https://github.com/ds2-lab/SFS){:target="\_blank"}] 





