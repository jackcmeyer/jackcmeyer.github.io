---
layout: project
title: "Wikipedia Quick Search"
subtitle: "A quick Wikipedia Search Chrome Extension"
category: "project"
author: "Jack Meyer"
---
<!-- Start Writing Below in Markdown -->
Wikipedia quick search is a Chrome Extension which allows users to highlight
a word on a webpage and do a quick Wikipedia search. It opens up Wikipedia
in a popup window and allows the user to see what they searched for. It is
perfect for searching people, places, teams, and events. This is the perfect
tool for when you are browsing web pages and you don't know something in an
article.

Since it is a Chrome Extension, it uses the Chrome Message Passing API to allow
the extension to communicate with the webpage. It injects a Content Script
into the current webpage to allow the value of the highlighted text to be sent
back to the extension.

When designing this tool, speed and a minimalist design were the goals. The UI
needed to be something that did not impact the what the user was looking at on
their main screen and it needed the search needed to be fast to actually be
useful. This is why directly searching the Wikipedia website and using a
popup window were the best choices. 
