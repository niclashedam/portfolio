---
layout: post
title: "Delilah implements hardware acceleration"
date: 2023-12-18 09:00:00+0100
inline: false
---

[Delilah](/projects/delilah/), my Computational Storage Processor (CSP), recently achieved a noteworthy milestone in our ongoing pursuit of innovation. In recent experiments, we successfully introduced hardware acceleration, representing a significant breakthrough for Delilah's capabilities.

This hardware acceleration, initially tailored to support filtering operations, enables the eBPF virtual machine within Delilah to schedule hardware acceleration tasks within the FPGA. Although the focus is currently on filtering operations, the preliminary results are encouraging, indicating potential improvements in program performance by offloading applicable operations to the FPGA.

We are cautiously optimistic about the promising direction these experiments have taken. While this breakthrough may not yet be transformative across all operations, it does signal a step forward in our commitment to refining Delilah's capabilities. Our intention is to share our findings in an upcoming paper.

The journey towards innovation is often incremental, and we are humbled by the progress made thus far. I look forward to sharing more updates and insights as we work towards further advancements in Delilah's capabilities and the broader landscape of computational storage processors.