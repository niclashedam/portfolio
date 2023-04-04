---
layout: page
title: Delilah
description: A Computational Storage Processor utilising eBPF developed at ITU.
img: assets/img/delilah.jpg
importance: 1
category: work
---
During my PhD studies at the [IT University of Copenhagen](https://en.itu.dk/), I had the opportunity to build an innovative Computational Storage Processor (CSP) known as Delilah. Delilah is designed to run on the Daisy OpenSSD and operates by exposing an asynchronous computational storage protocol to the host. The protocol uses [eBPF](https://en.wikipedia.org/wiki/EBPF) (extended Berkeley Packet Filter) to transform data and orchestrate I/O operations to the underlying storage media.

The development of computational storage processors like Delilah has revolutionized the field of data storage. These processors have enabled new computing models and support data-intensive applications, which would have been impossible with traditional storage systems. What sets Delilah apart is that it may be the first computational storage processor publicly described that employs eBPF. Moreover, since it utilizes eBPF, it is vendor-neutral and not dependent on any particular hardware or software vendor.

As a result of my research, I am looking forward to publishing a series of articles on Delilah in 2023 and 2024, coinciding with the release of NVMe TP 4091.

You can study the Delilah repositories on [GitHub](https://github.com/delilah-csp), where I've released all the Delilah repositories under Apache 2.0. Delilah is part of a DAPHNE, which is funded by the [Horizon 2020 research and innovation programme](https://ec.europa.eu/programmes/horizon2020/) under [grant agreement Nº957407](https://cordis.europa.eu/project/id/957407).