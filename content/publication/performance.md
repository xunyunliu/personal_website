+++
abstract = ""
abstract_short = ""
authors = ["Xunyun Liu","Rajkumar Buyya"]
date = 2017-06-10T20:19:18+10:00
highlight = true
image_preview = ""
math = false
publication = "IEEE Transactions on Big Data (TBD)"
publication_short = "IEEE Transactions on Big Data (TBD)"
publication_types = ["2"]
selected = false
title = "Performance-Oriented Deployment of Streaming Applications on Cloud"
url_code = ""
url_dataset = ""
url_pdf = "pdf/performance.pdf"
url_project = ""
url_slides = ""
url_video = ""

[header]
  caption = ""
  image = ""

+++


**Abstract**

Performance of streaming applications are significantly impacted by the deployment decisions made at infrastructure level, i.e., number and configuration of resources allocated for each functional unit of the application. The current deployment practices are mostly platform-oriented, meaning that the deployment configuration is tuned to a static resource-set environment and thus is inflexible to use in cloud with an on-demand resource pool. In this paper, we propose P-Deployer, a deployment framework that enables streaming applications to run on IaaS clouds with satisfactory performance and minimal resource consumption. It achieves performance-oriented, cost-efficient and automated deployment by holistically optimizing the decisions of operator parallelization, resource provisioning, and task mapping. Using a Monitor-Analyze-Plan-Execute (MAPE) architecture, P-Deployer iteratively builds the connection between performance outcome and resource consumption through task profiling and models the deployment problem as a bin-packing variant. Extensive experiments using both synthetic and real-world streaming applications have shown the correctness and scalability of our approach, and demonstrated its superiority compared to platform-oriented methods in terms of resource cost.


