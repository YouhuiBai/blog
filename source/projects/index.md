---
title: Projects
date: 2022-07-13 13:18:50
academia: true
---


---
### [<font color=CornflowerBlue>MindSpore</font>](https://gitee.com/mindspore/mindspore)
MindSpore is a new open source deep learning training/inference framework that could be used for mobile, edge and cloud scenarios. MindSpore is designed to provide development experience with friendly design and efficient execution for the data scientists and algorithmic engineers, native support for Ascend AI processor, and software hardware co-optimization. At the meantime MindSpore as a global AI open source community, aims to further advance the development and enrichment of the AI software/hardware application ecosystem.

---
### [<font color=CornflowerBlue>HiPress</font>](https://gitlab.com/hipress)
Gradient compression is a promising approach to alleviating the communication bottleneck in data parallel deep neural network (DNN) training by significantly reducing the data volume of gradients for synchronization. While gradient compression is being actively adopted by the industry (e.g., Facebook and AWS), our study reveals that there are two critical but often overlooked challenges: 1) inefficient coordination between compression and communication during gradient synchronization incurs substantial overheads, and 2) developing, optimizing, and integrating gradient compression algorithms into DNN systems imposes heavy burdens on DNN practitioners, and ad-hoc compression implementations often yield surprisingly poor system performance. In this project, we first propose a compression-aware gradient synchronization architecture, CaSync, which relies on a flexible composition of basic computing and communication primitives. It is general and compatible with any gradient compression algorithms and gradient synchronization strategies, and enables high-performance computationcommunication pipelining. We further introduce a gradient compression toolkit, CompLL, to enable efficient development and automated integration of on-GPU compression algorithms into DNN systems with little programming burden. Lastly, we build a compression-aware DNN training framework HiPress with CaSync and CompLL. HiPress is open-sourced and runs on mainstream DNN systems such as MXNet, TensorFlow, and PyTorch. Evaluation via a 16-node cluster with 128 NVIDIA V100 GPUs and 100Gbps network shows that HiPress improves the training speed over current compression-enabled systems (e.g., BytePS-onebit and Ring-DGC) by 17.2%-69.5% across six popular DNN models.

---
### [<font color=CornflowerBlue>PaGraph</font>](https://gitlab.com/adsl_ustc/open_source_projects/pagraph/-/tree/master)
Scaling GNN Training on Large Graphs via Computation-aware Caching and Partitioning. Build based on DGL with PyTorch backend. PaGraph in master branch supports data caching and graph partition. In overlap branch it additionally supports overlapping data loading and GPU computation.

---

<style>
hr:nth-of-type(1) {
  border-color: White !important;
}
hr:nth-of-type(2) {
  border-color: White !important;
}
hr:nth-of-type(3) {
  border-color: White !important;
}
hr:nth-of-type(4) {
  border-image: White !important;
}
hr:nth-of-type(5) {
  border-image: White !important;
}
</style>
