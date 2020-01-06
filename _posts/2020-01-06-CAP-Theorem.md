---
layout: entry
name: CAP Theorem
webpage: https://www2.eecs.berkeley.edu/Faculty/Homepages/brewer.html
description: "The CAP theorem by Eric Brewer states that any distributed system with shared data is likely to see tension between the following systemic properties:\n
\nConsistency - All the replicas are in sync and maintain the same state of any given object at any given point of time. Also known as sequential consistency.\n
\nAvailability - A request will eventually complete successfully. A read/write request on any node of the system will never be rejected as long as the particular node is up and running.\n
\nNetwork Partition Tolerance - When the network connecting the nodes goes down, the system will still continue to operate even though some/all nodes can longer communicate with each other.\n
\nAlternately, the theorem states that it is possible for the system to satisfy any two but not all of the properties mentioned above."
source: <a href="https://www.quora.com/What-Is-CAP-Theorem-1" target="_blank">Quora</a>
tags:
- Distributed Systems
---
