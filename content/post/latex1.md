+++
date = "2017-05-26T16:09:34+10:00"
highlight = false
math = false
tags = ["latex","troubleshooting"]
title = "Something's wrong--perhaps a missing \\item. \\end{thebibliography}"

[header]
  caption = ""
  image = ""

+++


When I compiled my manuscript for the first time, texstudio reports the following error message:

    Something's wrong--perhaps a missing \item. \end{thebibliography} 

I double checked the source code of the tex file but didn't find anything unusual.

Soon I realised that I have deleted all the citations in the main content, and that is why the error message is triggered. So the solution is simple: **add a citation from your library**.

