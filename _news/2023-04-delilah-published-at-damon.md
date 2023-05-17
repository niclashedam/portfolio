---
layout: post
title: "It's official! Delilah to be published and presented at DaMoN 2023"
date: 2023-05-17 09:00:00+0100
inline: false
---

[Delilah](/projects/delilah/), my novel Computational Storage Processor (CSP), has made history by becoming the first of its kind to be [publicly described](/papers/2023-DaMoN.pdf) and published. The achievements of Delilah will be highlighted in a paper titled "Delilah: eBPF-offload on Computational Storage," which I will present at the [19th International Workshop on Data Management on New Hardware (DaMoN)](https://sites.google.com/view/damon2023/) in June 2023. The event will take place in Seattle, Washington, United States, bringing together experts and researchers from the field.

Over the years, there have been numerous attempts to explore the idea of offloading computational tasks to storage devices. However, achieving widespread adoption has proven to be quite a challenge. That said, I'm hopeful about the potential breakthrough offered by the introduction of Computational Program namespaces in NVMe (TP 4091). This proposal introduces device-specific programs that can be installed statically, as well as downloadable programs that can be offloaded from a host dynamically using the extended Berkeley Packet Filter (eBPF).

In the paper, our focus is on sharing the design and implementation of Delilah. It represents the first public description of an actual computational storage device that supports eBPF-based code offload. We are diving into the nitty-gritty details of Delilah's architecture and providing insights into its practical applications. To better understand the device's performance, we conducted a series of experiments to evaluate the overhead associated with eBPF function execution in Delilah. Furthermore, we explored various design options, setting a solid foundation for future research and advancements in this field.

The publication of this paper not only highlights the remarkable achievements of Delilah but also marks an important milestone in the development and adoption of computational storage devices. By showcasing the feasibility and potential benefits of eBPF-offload on computational storage, Delilah opens up exciting possibilities for utilizing storage devices in advanced computations. I'm truly thrilled to contribute to the improved efficiency and performance of data management and processing through my work on Delilah.