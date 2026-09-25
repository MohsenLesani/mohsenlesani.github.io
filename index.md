<!-----
title: "Mohsen Lesani"
----->
<a name="home"></a> <div class="navbar"> [Home](#home) &nbsp;&nbsp; [Projects](#projects) &nbsp;&nbsp; [Papers](#papers) &nbsp;&nbsp; [Teaching](#teaching) &nbsp;&nbsp; [Service](#service) &nbsp;&nbsp; [Team](#team) &nbsp;&nbsp; [Other](#other) </div>

<!--<a name="home"></a> <div class="navbar"> |&nbsp; [Home](#home) &nbsp;|&nbsp; [Projects](#projects) &nbsp;|&nbsp; [Papers](#papers) &nbsp;|&nbsp; [Teaching](#teaching) &nbsp;|&nbsp; [Service](#service) &nbsp;|&nbsp; [Team](#team) &nbsp;|&nbsp; [Other](#other) &nbsp;| </div> -->

<!-- ********************************************** -->
<!-- | [Home](index.html) | [Projects](#projects) | [Papers](#papers) | [Teaching](#teaching) | [Service](#service) | [Team](#team) | [Other](#other) | -->
<!-- ********************************************** -->


<!-- ![](images/MohsenSC.jpg) -->
![](images/Mohsen.jpg)

Mohsen Lesani
[Associate Professor](https://campusdirectory.ucsc.edu/cd_detail?uid=mlesani)
[Computer Science and Engineering Department](https://engineering.ucsc.edu/departments/computer-science-and-engineering/)
[University of California, Santa Cruz](https://www.ucsc.edu/)

Contact: mlesani AT ucsc.edu

<p class="emph">
I have positions for motivated students. I will be glad to hear about your interests and accomplishments.
</p>

I am an associate professor at the Computer Science and Engineering Department of the University of California, Santa Cruz. I was a postdoc at MIT, obtained my PhD from UCLA, my MS in artificial intelligence from Sharif University of Technology and my BS in software engineering from University of Tehran. My research interests are reliability and security of software systems especially concurrent and distributed systems. Our recent focus is on secure replicated systems and AI-assisted verified system generation. I received the NSF CAREER award in 2020 and DARPA YFA award in 2022. My research has been recognized as SIGPLAN Research Highlight in 2019, received the distinguished paper award at OOPSLA 2018 and has been supported by multiple NSF grants.

**********************************************
# Projects

Here are some of our current and past projects: 

- **LLM-assisted Verified System Generation**
Given high-level system specifications including safety, liveness, and performance, can we generate both efficient systems and machine-checkable proofs of their correctness?
[NeurIPS'26](https://arxiv.org/abs/2605.23109)

- **Resilient and secure distributed systems**
Given resiliency requirements (confidentiality, integrity and especially availability policies) for an online service, how can we automatically partition, place and replicate it to ensure resiliency?
[S&P'22](companion/sp22/index.html)

- **Heterogeneous and reconfigurable secure distributed systems**
How can we replicate online services on untrusted, heterogeneous, and dynamic hosts?
[DISC'23](companion/disc23/index.html),  [DISC'24](companion/disc24/index.html),  [ICDE'25](companion/icde25/index.html),  [DC'26](companion/dc26/index.html)

- **Automatic analysis and synthesis of replicated objects**
Given a data type or a database and its integrity properties, how can we automatically decide the optimum hybrid consistency, and synthesize a custom replicated store that guarantees convergence and integrity? How can we accelerate hybrid consistency on message passing, RDMA and FPGA networks?
[POPL'19](companion/popl19/index.html),  [CAV'20](companion/cav20/index.html),  [PLDI'22](companion/pldi22/index.html),  [OOPSLA'25](companion/oopsla25/index.html),  [OOPSLA'26](companion/oopsla26/index.html),  [arXiv](https://arxiv.org/abs/2603.08003)

- **Verification of distributed systems**
How can we modularly build a certified stack of distributed components?
[POPL'16](companion/popl16/index.html),  [ICFP'20](companion/icfp20/index.html)

- **Data analytics**
Given high-level analytics queries in domain specific languages, how can we automatically optimize and synthesize efficient parallel and distributed workflows?
[ICFP'21](companion/icfp21/index.html)

- **Secure exchange**
How can we securely and efficiently execute transactions across multiple blockchains?
[ICBC'20](companion/icbc20/index.html),  [PODC'21](companion/podc21/index.html),  [CSF'23](companion/csf23/index.html)

- **Machine learning for performance models**
Can we learn performance characteristics of data structures and leverage it to synthesize efficient data structures?
[MAPL'20](companion/mapl20/index.html)

- **Domain-specific languages and type systems**
Can the safety guarantees of type systems carry over to safety of lab-on-a-chip assays?
[OOPSLA'18](companion/oopsla18/index.html),  [CACM'21](companion/cacm21/CACM21.pdf)

- **Automatic fence insertion for concurrent systems**
Given high-level required orders between instructions of the concurrent program in each thread, can we optimize and automate the subtle task of fence placement?
[OOPSLA'15](companion/oopsla15/index.html),  [PODC'17](companion/podc17/index.html),  [DISC'19](companion/disc19/index.html)

- **Concurrency programming models, testing and verification**
How can we design and implement intuitive, efficient and correct concurrent programming models, and data structures?
[PPoPP'11](downloads/Papers/PPoPP11.pdf),  [CONCUR'12](companion/concur12/index.html),  [DISC'13](companion/disc13/index.html),  [DISC'14](companion/disc14/index.html),  [CAV'14](companion/cav14/index.html),  [NFM'19](companion/nfm19/index.html),  [OOPSLA'22](companion/oopsla22/index.html)

**********************************************
# Papers
- SafarDB: FPGA-Accelerated Distributed Transactions via Replicated Data Types
Javad Saberlatibari, Prithviraj Yuvaraj, Philip Brisk, Mohammad Sadoghi, Mohsen
Lesani
[arXiv](https://arxiv.org/abs/2603.08003)

- Inductive Deductive Synthesis: Enabling AI to Generate Formally Verified Systems
S. Agarwal, A. Krentsel, S. Liu, M. Cemri, A. Cheng, R. Meng, T. Pfister, C. Li, S. Ratnasamy, A. Parameswaran, M. Zaharia, I. Stoica, M. Lesani
NeurIPS '26 oral (Neural Information Processing Systems)
[Paper](https://arxiv.org/abs/2605.23109)

- Frashokereti: Non-aborting Optimistically Replicated Objects
OOPSLA '26 (ACM SIGPLAN conference on Object-oriented Programming, Systems, Languages, and Applications)
Eric Chan, Javad Saberlatibari, Mohsen Lesani
[Paper](companion/oopsla26/OOPSLA26.pdf), [BibTex](companion/oopsla26/paper.bib), [More](companion/oopsla26/index.html)

- Satrapy: From Abstract to Practical Consensus for Heterogeneous Quorum Systems
Distributed Computing Journal 2026
Xiao Li, Eric Chan, Mohsen Lesani
[Paper](companion/dc26/DC26.pdf), [BibTex](companion/dc26/paper.bib), [More](companion/dc26/index.html)

- Hambazi: Spatial Coordination Synthesis for Augmented Reality
OOPSLA '25 (ACM SIGPLAN conference on Object-oriented Programming, Systems, Languages, and Applications)
Yi-Zhen Tsai, Jiasi Chen, Mohsen Lesani
[Paper](companion/oopsla25/OOPSLA25.pdf), [BibTex](companion/oopsla25/paper.bib), [More](companion/oopsla25/index.html)

- Hamava: Fault-tolerant Reconfigurable Geo-Replication on Heterogeneous Clusters
ICDE '25 (IEEE International Conference on Data Engineering)
Tejas Mane, Xiao Li, Mohammad Sadoghi, Mohsen Lesani
[Paper](companion/icde25/ICDE25.pdf), [BibTex](companion/icde25/paper.bib), [More](companion/icde25/index.html)

- TensorRight: Automated Verification of Tensor Graph Rewrites
POPL '25 (ACM SIGPLAN Symposium on Principles of Programming Languages)
J. Arora, S. Lu, D. Jain, T. Xu, F Houshmand, P. M. Phothilimthana, M. Lesani, P. Narayanan, K. S. Murthy, R. Bodik, A. Sabne, C Mendis
[Paper](companion/popl25/POPL25.pdf), [BibTex](companion/popl25/paper.bib)

- BA: Reconfigurable Heterogeneous Quorum Systems (short paper)
DISC '24 (The International Symposium on Distributed Computing)
Xiao Li, Mohsen Lesani
[Paper](companion/disc24/DISC24Full.pdf), [More](companion/disc24/index.html)

- Vulnerability Flow Type Systems
LangSec '24 (Language-theoretic Security and Applications Workshop at the IEEE Security & Privacy Symposium 2024)
Mohsen Lesani
[Paper](companion/langsec24/LangSec24.pdf), [More](companion/langsec24/index.html)

- Quorum Subsumption for Heterogeneous Quorum Systems
DISC '23 (The International Symposium on Distributed Computing)
Xiao Li, Eric Chan, Mohsen Lesani
[Paper](companion/disc23/DISC23.pdf), [More](companion/disc23/index.html)

- Cross-chain Swaps with Preferences
CSF '23 (IEEE Computer Security Foundations Symposium)
Eric Chan, Marek Chrobak, Mohsen Lesani
[Paper](companion/csf23/CSF23.pdf), [More](companion/csf23/index.html)

- Hamband: RDMA Replicated Data Types
PLDI '22 (ACM SIGPLAN Conference on Programming Language Design and Implementation)
Farzin Houshmand, Javad Saberlatibari, Mohsen Lesani
[Paper](companion/pldi22/PLDI22.pdf), [More](companion/pldi22/index.html)

- C4: Verified Transactional Objects
OOPSLA '22 (ACM SIGPLAN conference on Object-oriented Programming, Systems, Languages, and Applications)
M. Lesani, L. Xia, A. Kaseorg, C. Bell, A. Chlipala, B. Pierce, S. Zdancewic
[Paper](companion/oopsla22/OOPSLA22.pdf), [More](companion/oopsla22/index.html)

- Hamraz: Resilient Partitioning and Replication
S&P '22 (IEEE Symposium on Security and Privacy)
Xiao Li, Farzin Houshmand, Mohsen Lesani
[Paper](companion/sp22/SP22.pdf), [More](companion/sp22/index.html)

- Grafs: Declarative Graph Analytics
ICFP '21 (ACM SIGPLAN International Conference on Functional Programming)
Farzin Houshmand, Mohsen Lesani, Keval Vora
[Paper](companion/icfp21/ICFP21.pdf), [More](companion/icfp21/index.html)

- Brief Announcement: Brokering with Hashed Timelock Contracts is NP-Hard
PODC '21 (ACM Symposium on Principles of Distributed Computing)
Eric Chan, Mohsen Lesani
[Paper](companion/podc21/PODC21.pdf), [More](companion/podc21/index.html)

- BioScript: programming safe chemistry on laboratories-on-a-chip
CACM '21 (Communications of the ACM 64, 2, February 2021) 
Jason Ott, Tyson Loveless, Chris Curtis, Mohsen Lesani, and Philip Brisk. 2021.
[Paper](companion/cacm21/CACM21.pdf)

- TLC: Temporal Logic of Distributed Components
ICFP '20 (ACM SIGPLAN International Conference on Functional Programming)
Jeremiah Griffin, Mohsen Lesani, Narges Shadab, Xizhe Yin
[Paper](companion/icfp20/ICFP20.pdf), [More](companion/icfp20/index.html)

- Hampa: Solver-aided Recency-Aware Replication
CAV '20 (International Conference on Computer-Aided Verification)
Xiao Li, Farzin Houshmand, Mohsen Lesani
[Paper](companion/cav20/CAV20.pdf), [More](companion/cav20/index.html)

- UBITect: A Precise and Scalable Method to Detect Use-Before-Initialization bugs in Linux Kernel
ESEC/FSE '20 (The ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering)
Y. Zhai, Y. Hao, H. Zhang, D. Wang, C. Song, Z. Qian, M. Lesani, S. Krishnamurthy, P. Yu
[Paper](companion/fse20/FSE20.pdf), [More](companion/fse20/index.html)

- Cross-Chain Transactions
ICBC '20 (IEEE International Conference on Blockchain and Cryptocurrency)
Narges Shadab, Farzin Houshmand, Mohsen Lesani
[Paper](companion/icbc20/ICBC20.pdf), [More](companion/icbc20/index.html)

- Learning Quantitative Representation Synthesis
MAPL '20 (ACM SIGPLAN Machine Learning and Programming Languages Workshop)
Mayur Patil, Farzin Houshmand, Mohsen Lesani
[Paper](companion/mapl20/MAPL20.pdf), [More](companion/mapl20/index.html)

- Hamsaz: Replication Coordination Analysis and Synthesis
POPL '19 (ACM SIGPLAN Symposium on Principles of Programming Languages)
Farzin Houshmand, Mohsen Lesani
[Paper](companion/popl19/POPL19.pdf), [More](companion/popl19/index.html)

- Polynomial-time Fence Insertion For Structured Programs
DISC '19 (The International Symposium on Distributed Computing)
Mohammad Taheri, Arash Pourdamghani, Mohsen Lesani
[Paper](companion/disc19/DISC19.pdf), [More](companion/disc19/index.html)

- Transaction Protocol Verification with Labeled Synchronization Logic
NFM '19 (NASA Formal Methods Symposium)
Mohsen Lesani
[Paper](companion/nfm19/FullPaper.pdf), [More](companion/nfm19/index.html)

- BioScript: Programming Safe Chemistry of Laboratories-on-a-Chip
OOPSLA '18 (ACM SIGPLAN conference on Object-oriented Programming, Systems, Languages, and Applications)
Distinguished paper award
SIGPLAN Research Highlight 2019
Invited to Communications of ACM
Jason Ott, Chris Curtis, Tyson Loveless, Mohsen Lesani, Philip Brisk
[Paper](companion/oopsla18/OOPSLA18.pdf), [More](companion/oopsla18/index.html)

- Brief Announcement: Fence Insertion for Straight-line Programs is in P
PODC '17 (ACM Symposium on Principles of Distributed Computing)
Mohsen Lesani
[Paper](companion/podc17/PODC17.pdf), [More](companion/podc17/index.html)

- Chapar: Certified Causally Consistent Distributed Key-Value Stores
POPL '16 (ACM SIGPLAN Symposium on Principles of Programming Languages)
Mohsen Lesani, Christian J. Bell, Adam Chlipala
[Paper](companion/popl16/POPL16.pdf), [More](companion/popl16/index.html)

- Declarative Fence Insertion
OOPSLA '15 (ACM SIGPLAN conference on Object-oriented
Programming, Systems, Languages, and Applications)
John Bender, Mohsen Lesani, Jens Palsberg
[Paper](companion/oopsla15/OOPSLA15.pdf), [More](companion/oopsla15/index.html)

- AtomChase: Directed Search towards Atomicity Violations
ISSRE '15 (IEEE International Symposium on Software Reliability Engineering)
Mahdi Eslamimehr, Mohsen Lesani
Best paper award
[More](companion/issre15/index.html)

- Decomposing Opacity
DISC '14 (International Symposium on DIStributed Computing), WTTM '13
Mohsen Lesani, Jens Palsberg
[Paper](companion/disc14/DISC14.pdf), [More](companion/disc14/index.html)

- Automatic Atomicity Verification for Clients of Concurrent Data Structures
CAV '14 (International Conference on Computer Aided Verification)
Mohsen Lesani, Todd Millstein, Jens Palsberg
[Paper](companion/cav14/CAV14.pdf), [More](companion/cav14/index.html)

- On the Correctness of Transactional Memory Algorithms
PhD Dissertation
Mohsen Lesani
[Dissertation](companion/dissertation/Dissertation.pdf), [More](companion/dissertation/index.html)

- MrCrypt: Static Analysis for Secure Cloud Computations
OOPSLA '13 (ACM SIGPLAN conference on Object-oriented Programming, Systems, Languages, and Applications)
Sai Deep Tetali, Mohsen Lesani, Rupak Majumdar, Todd Millstein
[Paper](companion/oopsla13/Oopsla13.pdf), [More](companion/oopsla13/index.html)

- Proving Non-opacity
DISC '13 (International Symposium on DIStributed Computing), Transact'13
Mohsen Lesani, Jens Palsberg
[Paper](companion/disc13/DISC13.pdf), [More](companion/disc13/index.html)

- A Framework for Formally Verifying Software Transactional Memory Algorithms
CONCUR '12  (International Conference on Concurrency Theory)
Mohsen Lesani, Victor Luchangco, Mark Moir
[Paper](companion/concur12/CONCUR12.pdf), [More](companion/concur12/index.html)

- Communicating Memory Transactions
PPoPP '11 (ACM Principles and Practice of Parallel Programming)
Mohsen Lesani, Jens Palsberg
[Paper](downloads/Papers/PPoPP11.pdf)

- Semantics-preserving Sharing Actors
AGERE '13 (ACM Workshop on Programming based on Actors, Agents, and Decentralized Control)
Mohsen Lesani, Antonio Lain
[Paper](companion/agere13/Paper.pdf), [More](companion/agere13/index.html)

- Specifying Transactional Memories with Nontransactional Operations
WTTM '13  (Workshop on the Theory of Transactional Memory)
Mohsen Lesani, Victor Luchangco, Mark Moir
[Paper](companion/wttm13_2/Paper.pdf)

- Putting Opacity in its Place
WTTM '12  (Workshop on the Theory of Transactional Memory)
Mohsen Lesani, Victor Luchangco, Mark Moir
[Paper](downloads/Papers/WTTM12.pdf)

- Fuzzy Trust Aggregation And Personalized Trust Inference In Virtual Social Networks
Journal of Computational Intelligence 25/2, 2009
Mohsen Lesani, Niloufar Montazeri
[Paper](downloads/Papers/JCI09.pdf)

- Aria Language, Towards Agent Orientation Paradigm
ICSOFT '08 (International Joint conference on Software Technologies)
Mohsen Lesani, Niloufar Montazeri
[Paper](downloads/Papers/ICSOFT08.pdf)

- Successful Cooperation between Heterogeneous Fuzzy Q-Learning Agents
SMC '04 (IEEE International Conference on Systems, Man, and Cybernetics)
Ali Akhavan Bitaghsir, Amir Moghimi, Mohsen Lesani, Mohammad Mehdi Keramati, Majid Nili Ahmadabadi, Babak Nadjar Arabi
[Paper](downloads/Papers/SMC04.pdf)

[The rest of papers](restofpapers.html)


**********************************************
# Teaching

UCSC
   [CSE 232: Distributed Systems](https://mohsenlesani.github.io/slugcse232/),
<!--    S'25 -->
   [CSE 113: Parallel and Concurrent Programming](https://mohsenlesani.github.io/slugcse113/)
<!--    F'24 -->

UCR
   CS 160: Concurrent Programming and Parallel Systems, F'22
   [CS 179E: Project in Computer Science, compilers](teaching/cp/cp.html), Su'22
   [CS 247: Principles of Distributed Computing](teaching/podc.pdf), F'23
   [CS 246: Software Verification](teaching/sv.html), W'22
   CS 260: Seminar in Program Synthesis, F'17
   CS 260: Seminar in Distributed Computing, S'19


**********************************************
# Service

- [POPL '27](https://conf.researchr.org/home/POPL-2027), PC (ACM SIGPLAN Symposium on Principles of Programming Languages, Program Committee)
- [OOPSLA '26](https://splashcon.org/), PC (ACM SIGPLAN Conference on Object-oriented Programming, Systems, Languages, and Applications, Program Committee)
- [CSF '25](https://csf2025.ieee-security.org/), general co-chair (IEEE Computer Security Foundations Symposium)
- [PODC '25](https://www.podc.org/podc2025/), PC (The ACM Symposium on Principles of Distributed Computing, Program Committee)
- [PLDI '25](https://pldi25.sigplan.org/), PC (ACM SIGPLAN Conference on Programming Language Design and Implementation, Program Committee)
- [DISC '24](https://www.disc-conference.org/wp/disc2024/), PC (The International Symposium on DIStributed Computing, Program Committee)
- [CCS '24](https://www.sigsac.org/ccs/CCS2024/home.html), PC (ACM Conference on Computer and Communications Security, Program Committee)
- [S&P '24](https://sp2024.ieee-security.org/index.html), OC (IEEE Symposium on Security and Privacy, Organizing Committee, Short Talks Chair)
- [ASIACCS '24](https://asiaccs2024.sutd.edu.sg/), PC (ACM ASIA Conference on Computer and Communications Security, Program Committee), round 1
- [PLDI '23](https://pldi23.sigplan.org/), PC (ACM SIGPLAN Conference on Programming Language Design and Implementation, Program Committee)
- [POPL '23](https://conf.researchr.org/home/POPL-2023), PC (ACM SIGPLAN Symposium on Principles of Programming Languages, Program Committee)
- [CCS '22](https://www.sigsac.org/ccs/CCS2022/), OC (ACM Conference on Computer and Communications Security, Organizing Committee, Grant chair)
- [AFT '22](https://aft.acm.org/aft22/index.html), PC (ACM conference on Advances in Financial Technologies, Program Committee)
- OOPSLA '21, PC (ACM SIGPLAN Conference on Object-oriented Programming, Systems, Languages, and Applications, Program Committee)
- OOPSLA '20, PC (ACM SIGPLAN Conference on Object-oriented Programming, Systems, Languages, and Applications, Program Committee)
- DisCoTec '20, PC (International Federated Conference on Distributed Computing Techniques, Program Committee)
POPL '20, PC (ACM SIGPLAN Symposium on Principles of Programming Languages, Program Committee)
- ECOOP '18, PC (European Conference on Object-Oriented Programming, Program Committee)
- POPL '17, ERC (ACM Principles of Programming Languages 2017, External Review Committee)
- CPP '17, PC (ACM Certified Programs and Proofs 2017, Program Committee)

**********************************************
# Team

We work together at the Safe and Secure Software (S3) lab.

![](images/students/XiaoS.jpg)

<!-- <ul class="air"> -->
[Xiao Li](https://xiaoli0614.github.io/), PhD student
Primary publications: [CAV ’20](companion/cav20/index.html),  [S&P ’22](companion/sp22/index.html),  [DISC '23](companion/disc23/index.html),  [DISC '24](companion/disc24/index.html)
<!-- </ul> -->

![](images/students/EricS.jpg)

<!-- <ul class="air"> -->
Eric Chan, PhD student
Primary publications: [PODC ’21](companion/podc21/index.html),  [CSF '23](companion/csf23/index.html),  [OOPSLA'26](companion/oopsla26/index.html)
<!-- </ul> -->

![](images/students/JavadS.jpg)

<!-- <ul class="air"> -->
[Javad Saber-Latibari](https://www.cs.ucr.edu/%7Ejsabe004/), PhD student
Primary publications: [PLDI ’22](companion/pldi22/index.html)
<!-- </ul> -->

![](images/students/TejasS.jpg "Tejas")

<!-- <ul class="air"> -->
Tejas Mane, PhD student
Primary publications: [ICDE '25](companion/icde25/index.html)
<!-- </ul> -->

**********************************************
# Other

- I am from the beautiful city of Kerman where the Prince's Garden [1](images/PrinceGarden.jpg), [2](images/PrinceGarden2.jpg) is located.
- My [PhD hooding](https://drive.google.com/file/d/1vQg0X31CxArZsDSt-X2sL2VJDcyuQ-0I/view?usp=sharing) at UCLA.
- I tried acting and played John J. Astor in Titanic the musical. Can you find me in the [cast](images/Titanic.jpg)?
- I try to keep the [positive feedbacks](companion/reviews/index.html) that we get.
- The [names](names.html) of our papers.

**********************************************
