+++
title = "Message Broadcaster Demo for Distributed Systems"
date = 2018-08-20T10:25:19+10:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["java","demonstration"]
categories = []
summary = "a demo of multi-threading and sockect communication in Java"

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = "MessageBroadcaster.png"
caption = "[Github link](https://github.com/xunyunliu/MessageBroadcasterDemo)"
preview = true

+++

A message broadcaster implemented in a client-server architecture to demonstrate the use of multi-threading and socket communication in Java.

- Clients read server IP/port from config file
- Clients establish a TCP connection with the server
- Users type a message using the console, the client sends it to the server, the server broadcasts that message to all clients currently connected (including the sending client) and the clients display the message to the user.

{{< gdocs src="https://docs.google.com/presentation/d/e/2PACX-1vStygvWfjZOWOIjuDCT1exjyc9agUgP8Z_uAFIpw83mTsmHl8rzMCkdVq2ErqVteMMvG-PURZGsVmSd/embed?start=false&loop=false&delayms=3000" >}}

{{% staticref "pdf/messagebroadcaster.pdf" "newtab" %}}Download the slide for this demo.{{% /staticref %}}

Code can be found here: [github](https://github.com/xunyunliu/MessageBroadcasterDemo).