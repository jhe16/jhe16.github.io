---
title: "CS225: Advanced Distributed Systems"
collection: teaching
type: "Graduate course"
permalink: /teaching/2014-spring-teaching-1
venue: "1A-108, SIST, ShanghaiTech University"
date: 2022-01-01
location: "City, Country"
---

This course explores design and implementation principles in modern distributed systems. In particular, the course will emphasize on recent techniques used by real-world distributed systems such as cloud systems, enterprise data center, and virtualized container systems. Topics include canonical distributed concepts such as remote procedure call, replication, distributed system security, consensus protocol, and recent distributed system technologies such as peer-to-peer, grid, autonomic computing, distributed massive data processing/Google map-reduce, machine learning for distributed systems, distributed system debugging, multi-core systems, distributed virtualization.

Prerequisites
======
CS130 and CS120 or equivalents. Programming in C++ or Java in Unix environment. If you are not sure whether you can attend this course, please consult the instructor.

Tentative Grading Policy
======
Quiz and class participation: 15%, paper presentation: 15%, written reviews: 20%, project 50% (proposal writeup 5%, proposal presentation 5%, project midreview presentation 10%, demo 10%, final presentation 10%, final writeup 10%)

Late Policy
======
Calculated by the time recorded in the assignment emails received to the instructor. Students will lose 20% for each 24-hour period they are late on reviews, project, or paper.

Textbooks
======
1. Distributed systems principles and paradigms, Andrew S. Tanenbaum and Maarten van Steen, ISBN: 0-13-239227-5, Pearson, 2007. \[[online version](https://www.distributed-systems.net/index.php/books/ds3/ds3-ebook/)\]
2. Distributed Systems: Concepts and Design, George Coulouris, Jean Dollimore, Tim Kindberg, and Gordon Blair, ISBN: 978-0132143011, Pearson, 2011.

Paper Review Guidelines
======
Provide a paragraph of summary about the paper, a paragraph of 2-3 strong points of the paper (i.e., why the paper should be accepted), a paragraph of 2-3 weak points of the paper (i.e., why the paper should be rejected),  brainstorming ideas for developing new research ideas related to the work described in the paper.

Projects
======
Suggested topics:
1. Virtual Machine Management in Distributed Computing Environments
2. System Monitoring & Behavior Learning for Anomaly Detection
3. Distributed System Diagnosis Using Console Logs or Traces

Course project environments: HPC cluster, Amazon AWS, Google cloud

Both project proposal and final report should follow typical paper requirements using [ACM Double-Column Paper format](https://www.acm.org/publications/authors/submissions). The project proposal should include abstract, introduction, proposed approaches, and related work. The final project report should include a full paper content including abstract, introduction, design and algorithms, experiment evaluation, related work, and conclusion. The expected project report's length is 6 pages excluding references. We will organize a mini-conference for the students to present their project work. Three best papers will be selected during the mini-conference.

Class Schedule (Tentative)
======

| Date         | Topic                            | Assignments |
|--------------|----------------------------------|-------------|
| 2/15         | Introduction                     |         |
| 2/17         | Distributed system concepts      | 2/21 midnight: review due for [Time, clocks and the ordering of events in a distributed system](http://lamport.azurewebsites.net/pubs/time-clocks.pdf), L. Lamport, Communications ACM 1978.          |         
| 2/22         |   Distributed system fundamentals                   |        |
| 2/24         | Distributed system fundamentals     | 2/28 midnight: review due for [Distributed snapshots: determining global states of distributed systems](https://dl.acm.org/doi/10.1145/214451.214456), Chandy and Lamport, ACM TOCS 1985.         | 
| 3/1        |   Distributed system fundamentals                   |        |
| 2/3         | Distributed system fundamentals     | 3/7 midnight: review due for Rowstron and P. Druschel, “Pastry: Scalable, distributed object location and routing for large-scale peer-to-peer systems“.  Middleware, 2001.         | 
| 3/8        |   Remote procedure calls                   |        |
| 3/10         | Remote procedure calls     | 3/14 midnight: review due for Ion Stoica, Robert Morris, David Karger, M. Frans Kaashoek, and Hari Balakrishnan, “Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications“, Proc. of SIGCOMM, 2001.  3/14 midnight: Paper presentation signup due. Please send an email to the TA to bid three papers in the list below and list your choices in decreasing order. You will be allocated with one paper to present based on the FCFS policy and paper availability.  | 
| 3/15        |   Replications                   |        |
| 3/17         | Replications     | 3/21 midnight: review due for I. Cohen and M. Goldszmidt and T. Kelly and J. Symons and J. S. Chase, Correlating Instrumentation Data to System States: A Building Block for Automated Diagnosis and Control, Proc. of OSDI, 2004.         | 
| 3/22        |   Peer-to-Peer systems                  |        |
| 3/24        | Peer-to-Peer Systems     | 3/28 midnight: project proposal due.         | 
| 3/29        |   Project proposal presentations                  |        |
| 3/31        | Fault Tolerance     | 4/4 midnight: review due for I. Cohen and S. Zhang and M. Goldszmidt and J. Symons and T. Kelly and A. Fox, Capturing, indexing, clustering, and retrieving system history, Proc. of SOSP, 2005.       | 
| 4/5        |   Data-intensive computing                 |        |
| 4/7        | Data-intensive computing     | 4/11 midnight: review due for Daniel Dean, Hiep Nguyen, Xiaohui Gu, Hui Zhang, Junghwan Rhee, Nipun Arora, Geoff Jiang, PerfScope: Practical Online Server Performance Bug Inference in Production Cloud Computing Infrastructures, Proc. of SOCC 2014.       | 
| 4/12        |   Virtualization and cloud computing                 |        |
| 4/14        | Virtualization and cloud computing     | 4/18 midnight: review due for Martín Abadi et al., TensorFlow: A System for Large-Scale Machine Learning, Proc. of OSDI 2016.       | 
| 4/19        |   Distributed file systems                 |        |
| 4/21        | Distributed file systems     | 4/25 midnight: review due for Hiep Nguyen, Zhiming Shen, Xiaohui Gu, Sethuraman Subbiah, John Wilkes, AGILE: elastic distributed resource scaling for Infrastructure-as-a-Service, Proc. of USENIX International Conference on Autonomic Computing (ICAC), San Jose, CA, June, 2013.  | 
| 4/26        |   Project mid-review presentations                |        |
| 4/28        | System research methodology     | No paper reading assigned. You should spend time on your term projects.  | 
| 5/3        |   Student paper presentation                 |        |
| 5/5        | Student paper presentation     | No paper reading assigned. You should spend time on your term projects.  | 
| 5/10        |   Student paper presentation                 |        |
| 5/12        | Student paper presentation     | No paper reading assigned. You should spend time on your term projects.  | 
| 5/17        |   Student paper presentation                 |        |
| 5/19        | Student paper presentation     | No paper reading assigned. You should spend time on your term projects.  | 
| 5/24        |   Student paper presentation                 |        |
| 5/26       | Project demo    | No paper reading assigned. You should spend time on your term projects.  | 
| 5/31        |   Final project presentation                |        |
| 6/2       |  Final project presentation    | 6/6 midnight: final project report due, project source code and document due. Your project source code and document submission should be a single zip file. The zip file should include your system source code including all other dependent packages, the experimental subjects used in the project report, instructions on how to set up and use the system to reproduce the experimental results, and other documents that help others understand your tool and source code.  | 



Suggested Topics for Student Presentations
======
1. Guangpu Li, Shan Lu, Madanlal Musuvathi, Suman Nath, Rohan Padhye, Efficient Scalable Thread-Safety-Violation Detection, Proc. of SOSP 2019. 
2. Yongle Zhang, Kirk Rodrigues, Yu Luo, Michael Stumm, Ding Yuan, The Inflection Point Hypothesis: A Principled Debugging Approach for Locating the Root Cause of a Failure, Proc. of SOSP 2019. 
3. Ting Dai, Jingzhu He, Xiaohui Gu, Shan Lu, and Peipei Wang, DScope: Detecting Real-World Data Corruption Hang Bugs in Cloud Server Systems, Proc. of ACM Symposium on Cloud Computing (SOCC), Carlsbad, CA, October, 2018. 
4. Hiep Nguyen, Zhiming Shen, Yongmin Tan, Xiaohui Gu, FChain: Toward Black-box Online Fault Localization for Cloud Systems, Proc. of ICDCS 2013. 
5. Tuomas Pelkonen Scott Franklin Justin Teller Paul Cavallaro Qi Huang Justin Meza Kaushik Veeraraghavan, Gorilla: A Fast, Scalable, In-Memory Time Series Database, Proc. of VLDB 2015. 
6. Benjamin H. Sigelman, Luiz Andre Barroso, Mike Burrows, Pat Stephenson, ´ Manoj Plakal, Donald Beaver, Saul Jaspan, Chandan Shanbhag, Dapper, a Large-Scale Distributed Systems Tracing Infrastructure, Google Technical Report. 
7. Philipp Moritz et al., Ray: A Distributed Framework for Emerging AI Applications, Proc. of OSDI 2018. 
8. Yunseong Lee, et al., M. Zaharia, T. Das, H. Li, T. Hunter, S. Shenker, and I. Stoica, Discretized Streams: Fault-Tolerant Streaming Computation at Scale, Proc. of SOSP 2013. 
9. Shoumik Palkar and Matei Zaharia, Optimizing Data-Intensive Computations in Existing Libraries with Split Annotations, Proc. of SOSP 2019. 
10. Zhiming Shen, Sethuraman Subbiah, Xiaohui Gu, and John Wilkes, CloudScale: Elastic Resource Scaling for Multi-Tenant Cloud Systems, Proc. of ACM SOCC 2011. 
11. Guiseppe DeCandia et al, Dynamo: Amazon’s Highly Available Key-Value Store, Proc. of SOSP 2007. 
12. James C. Corbett et al., Spanner: Google’s Globally-Distributed Database, Proc. of OSDI 2012. 
13. Tyler Hunt, Zhiting Zhu, Yuanzhong Xu, Simon Peter, and Emmett Witchel, Ryoan: A Distributed Sandbox for Untrusted Computation on Secret Data, Proc. of OSDI 2016. 
14. Antonis Papadimitriou et al., Big Data Analytics over Encrypted Datasets with Seabed , Proc. of OSDI 2016. 
15. Yan Zhai et al., CQSTR: Securing Cross-Tenant Applications with Cloud Containers, Proc. of SOCC 2016. 

Academic Integrity
======
The university provides a detailed policy on academic integrity. 
Academic dishonesty (e.g., cheating or plagiarism) will not be tolerated under any circumstances. If you are having difficulty with any part of the course material, please see me as soon as possible. I will do everything I can to help you with any course-related problems you may be having. If you are found to be guilty of academic dishonesty, however, I will then do everything I can to see that you are punished as forcefully as possible. This may include asking to have you suspended or expelled from the course, the program, and/or the university. At a minimum, you will receive -50% for the assignment in question, and your name will be placed on record with the university as having committed an academic offence. Multiple offences during your academic career will result in suspension or expulsion from the university. I take absolutely no pleasure in pursuing cases of academic misconduct, and would ask that you please do not put me in this position.



