+++
abstract = ""
abstract_short = ""
authors = ["Xunyun Liu", "Aaron Harwood", "Shanika Karunasekera", "Benjamin Rubinstein",  "Rajkumar Buyya"]
date = "2017-05-25T16:55:29+10:00"
highlight = true
image_preview = ""
math = false
publication = "The 46th International Conference on Parallel Processing (ICPP-2017)"
publication_short = "The 46th International Conference on Parallel Processing (ICPP-2017)"
publication_types = ["1"]
selected = false
title = "E-Storm: Replication-based State Management in Distributed Stream Processing Systems"
url_code = ""
url_dataset = ""
url_pdf = "pdf/replication.pdf"
url_project = ""
url_slides = "ppt/replication.pptx"
url_video = ""

[header]
  caption = ""
  image = ""

+++

**Abstract**

Apache Storm is a fault-tolerant, distributed in-memory computation system for processing large volumes of high-velocity data in real-time. As an integral part of the fault-tolerance mechanism, Storm's  state management is achieved by a checkpointing framework, which commits  states regularly and recovers lost states from the latest checkpoint. However, this method involves a remote data store for state preservation and access, resulting in significant overheads to the performance of error-free execution. 

In this paper, we propose E-Storm, a replication-based state management system that actively maintains multiple state backups on different worker nodes. We build a prototype on top of Storm by extending it with monitoring and recovery modules to support inter-task state transfer whenever needed. The experiments carried out on synthetic and real-world streaming applications confirm that E-Storm outperforms the existing checkpointing method in terms of the resulting application performance, obtaining as much as 9.44 times throughput improvement while reducing the application latency down to 9.8%.

