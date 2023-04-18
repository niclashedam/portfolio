---
layout: post
title: "Delilah research leads to the introduction of variable-sized BPF stacks"
date: 2023-04-18 09:00:00+0100
inline: false
---

[Delilah](/projects/delilah/) research in collaboration with [TU Dresden](https://wwwdb.inf.tu-dresden.de/) has led to the introduction of variable-sized BPF stacks in the [LLVM compiler infrastructure](https://llvm.org/). This research is a significant step towards the emergence of eBPF as a general-purpose programming language for computational storage. Before this development, the BPF stack size was rigidly fixed at 512 bytes, severely limiting specific applications' capacity.

TU Dresden is utilizing two Delilah systems from the IT University of Copenhagen. While experimenting with loop-unrolling efficiency, it became apparent that the BPF stack size was prone to exhaustion. The LLVM compiler infrastructure was modified to allow for variable-sized BPF stacks, as proposed in differential [D147707](https://reviews.llvm.org/D147707). The LLVM reviewers successfully incorporated the modification into the LLVM main branch on April 17th, 2023.

In the past, the BPF stack size was limited to 512 bytes due to resource constraints in the kernel. However, in computational storage, such restrictions are rarely applicable. As a result, developers can now expand the BPF stack size up to the available memory of the eBPF program, which could amount to gigabytes. Soon, we plan to increase the stack size on Delilah to 1 MB. This development marks a significant milestone toward eBPF's emergence as a universal programming language for computational storage.