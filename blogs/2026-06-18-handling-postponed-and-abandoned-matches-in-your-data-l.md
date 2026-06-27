---
title: "Handling Postponed and Abandoned Matches in Your Data Layer"
url: "https://www.sportmonks.com/blogs/handling-postponed-and-abandoned-matches-in-your-data-layer/"
date: "2026-06-18"
author: "David Jaja"
feed_url: "https://www.sportmonks.com/blogs/feed/"
---
Postponed and abandoned matches are a persistent data problem for football applications, requiring apps to detect state transitions and respond correctly by removing fixtures from live displays while retaining records with updated states. The article advises treating fixture state as a dynamic state machine, polling the Sportmonks API's state field, and maintaining state transition histories in the database.
