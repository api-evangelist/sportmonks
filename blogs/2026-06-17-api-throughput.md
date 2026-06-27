---
title: "API Throughput"
url: "https://www.sportmonks.com/blogs/api-throughput/"
date: "2026-06-17"
author: "David Jaja"
feed_url: "https://www.sportmonks.com/blogs/feed/"
---
API throughput is the number of successful requests an API can process per unit of time, typically expressed as requests per second (RPS) or requests per minute (RPM), and represents the architectural constraint during peak usage. The article notes Sportmonks handles over 6.4 billion requests monthly and recommends 30-second TTL caching, using the include parameter to retrieve related data in single requests, and segmenting polling frequency by data freshness needs.
