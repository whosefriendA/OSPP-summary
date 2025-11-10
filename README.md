# OSPP 2025 @ Karmada Community  
## Project Summary  
**Project:** *Karmada cluster failover optimization*

---

## My OSPP Journey

My OSPP journey began with exploring **Karmada**. Initially, I delved into the official documentation to understand its core architecture and design philosophy. To truly grasp its working principles, I then dove into the source code, analyzing the implementation details of each module, especially the mechanics of the **TaintManager** and controllers.

This was a learning process that went from a **macro** to a **micro** level, giving me a more concrete understanding of the complexities of **cloud-native multi-cloud orchestration**.

While working on my main topic of *Optimizing Failover*, I identified the **Eviction Queue** as a critical and indispensable prerequisite. To better advance the project, I took the initiative to design and implement this fundamental component.

Throughout this process, I maintained close communication with my community mentor, compiling my ideas into a detailed **design document**. I presented this design at the community's **weekly meeting** and refined it through several iterations based on valuable feedback from my mentor and senior community members. This **open and transparent collaboration model** was incredibly beneficial.

Currently, the **core implementation** of the eviction queue is complete, and the relevant **PRs have been submitted**. However, the planned pluggable management component will require further design and implementation in a future release.

---

## Contribution List (Pull Requests)

- [Design of dynamic rate configuration and indicators for queues and their documents](https://github.com/karmada-io/karmada/pull/6613)  
- [Implementation of dynamic rate control eviction queue and indicators](https://github.com/karmada-io/karmada/pull/6675)  
- [API change EvictionQueueOptions to configure dynamic rate limit](https://github.com/karmada-io/karmada/pull/6777)
- [Metircs to improve the Observability of failover evictionqueue ](https://github.com/karmada-io/karmada/pull/6778)
- [Profiling Karmada zh documentation](https://github.com/karmada-io/website/pull/841)  
- [Karmada contributor zh documentation](https://github.com/karmada-io/website/pull/842)
- [Boundary fixes and test changes for the taint manager (to be discussed and modified later after consultation)](https://github.com/karmada-io/karmada/pull/6605)  
- [Resource cleanup plug-in function implementation and test coverage (follow up in subsequent versions)](https://github.com/karmada-io/karmada/pull/6709)  

---

## Summary & Outlook

This OSPP experience has been a **valuable period of growth** for me. It was not just a technical exercise; it allowed me to deeply experience the **charm of open source**.

From my initial confusion when facing a large codebase to being able to independently design and contribute code, every step was made possible with the **community's help**. Open discussions, rigorous code reviews, and selfless knowledge sharing—these are the **cornerstones of open-source collaboration**. They've transformed me from a mere code user into a **contributor**.

Although OSPP is coming to an end, this is just the **beginning of my open-source journey**.

