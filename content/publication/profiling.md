+++
abstract = ""
abstract_short = ""
authors = ["Xunyun Liu","Amir Vahid Dastjerdi","Rodrigo N. Calheiros", "Chenhao Qu", "Rajkumar Buyya"]
date = 2017-07-28T15:19:31+10:00
highlight = true
image_preview = ""
math = false
publication = "ACM Transactions on Autonomous and Adaptive Systems (TAAS)"
publication_short = "ACM Transactions on Autonomous and Adaptive Systems (TAAS)"
publication_types = ["2"]
selected = false
title = "A Stepwise Auto-Profiling Method for Performance Optimization of Streaming Applications"
url_code = ""
url_dataset = ""
url_pdf = "pdf/profiling.pdf"
url_project = ""
url_slides = ""
url_video = ""

[header]
  caption = ""
  image = ""

+++

**Abstract**

Data stream management systems (DSMSs) are scalable, highly available, and fault-tolerant systems that aggregate and analyze real-time data in motion. To continuously perform analytics on the fly within the stream, state-of-the-art DSMSs host streaming applications as a set of inter-connected operators, with each operator encapsulating the semantic of a specific operation. For parallel execution on a particular platform, these operators need to be appropriately replicated in multiple instances that split and process the workload simultaneously. Because the way operators are partitioned affects the resulting performance of streaming applications, it is essential for DSMSs to have a method to compare different operators and make holistic replication decisions to avoid performance bottlenecks and resource wastage. To this end, we propose a stepwise profiling approach to optimize application performance on a given execution platform. It automatically scales distributed computations over streams based on application features and processing power of provisioned resources, and builds the relationship between provisioned resources and application performance metrics to evaluate the efficiency of the resulting configuration. Experimental results confirm that the proposed approach successfully fulfils its goals with minimal profiling overhead.
