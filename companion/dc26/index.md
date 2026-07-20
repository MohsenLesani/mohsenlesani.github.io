<!-----
title: "Satrapy: From abstract to practical consensus for heterogeneous quorum systems"
----->

<div class="right"> |&nbsp; [Home](../../index.html) &nbsp;|&nbsp; [Projects](../../index.html#projects) &nbsp;|&nbsp; [Papers](../../index.html#papers) &nbsp;| </div>

**************************************************
**Satrapy: From abstract to practical consensus for heterogeneous quorum systems**
Distributed Computing (2026) 39:16
Xiao Li, Eric Chan, Mohsen Lesani

The traditional Byzantine quorum-system model assumes a pre-existing, global agreement on the set of quorums (typically defined as the sets consisting of more than two-thirds of the participants). This assumption is problematic in permissionless systems, which strive to allow anyone to join or leave the system dynamically. While proof-of-stake permissionless systems like Ethereum require newly joining participants to register into the system, other permissionless systems like the Ripple Ledger or the Stellar network allow participants to join the system without synchronization by forgoing agreement on the set of quorums. This results in what we call a heterogeneous quorum system, where each participant has its own, personal set of quorums. An important question is to determine under what condition is it possible to solve synchronization problems like reliable broadcast or consensus in a heterogeneous quorum system. In this work, we show that the traditional quorum intersection and quorum availability conditions are not sufficient in heterogeneous quorum systems. Moreover, we propose quorum subsumption, a new condition which, together with quorum availability and quorum intersection, is sufficient to allow solving reliable broadcast and consensus. Finally, we propose protocols for reliable broadcast and consensus in heterogeneous quorum systems that satisfy quorum subsumption. In particular, we present a practical consensus protocol called Satrapy which in contrast to abstract consensus protocols uses finite state and messages.

\[[Paper](DC26.pdf)\]
\[[BibTex](paper.bib)\]

```bibtex
@article{li2026satrapy,
  title={Satrapy: From abstract to practical consensus for heterogeneous quorum systems: X. Li, EM Chan, M. Lesani},
  author={Li, Xiao and Chan, Eric M and Lesani, Mohsen},
  journal={Distributed Computing},
  volume={39},
  number={2},
  pages={16},
  year={2026},
  publisher={Springer}
}
```

**************************************************
