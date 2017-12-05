+++
abstract = ""
abstract_short = ""
authors = ["Xunyun Liu", "Rajkumar Buyya"]
date = "2017-05-05T11:50:31+10:00"
highlight = true
image_preview = ""
math = false
publication = "The 23rd IEEE International Conference on Parallel and Distributed Systems (ICPADS 2017)"
publication_short = "The 23rd IEEE International Conference on Parallel and Distributed Systems (ICPADS 2017)"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]
selected = false
title = "D-Storm: Dynamic Resource-Efficient Scheduling of Stream Processing Applications"
url_code = ""
url_dataset = ""
url_pdf = "pdf/scheduling.pdf"
url_project = ""
url_slides = "pdf/icpads-presentation.pdf"
url_video = ""

[header]
  caption = ""
  image = ""

+++

**Abstract**

Scheduling streaming applications in Data Stream Management Systems (DSMS) has been investigated for years. However, there lacks an intelligent system that is capable of monitoring application execution, modelling its resource usages, and then adjusting the scheduling plan under different sizes of inputs  without requiring users' intervention. 
In this paper, we model the scheduling problem as a bin-packing variant and propose a heuristic-based algorithm to solve it with minimised inter-node communication. We also implement the D-Storm prototype to validate the efficacy and efficiency of our scheduling algorithm, by extending the Apache Storm framework into a self-adaptive MAPE (Monitoring, Analysis, Planning, Execution) architecture. The evaluation carried out on both synthetic and realistic applications proves that D-Storm outperforms the existing resource-aware scheduler and the default Storm scheduler by at least 16.25% in terms of the inter-node traffic reduction and yields a significant amount of resource savings through consolidation.
