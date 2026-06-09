---
num: lec2

name: Is Synchrony Back? A Path to Efficient and Sustainable Replication

speakers:
  - Fernando Pedone
  
affiliations:
  - Università della Svizzera italiana (USI)
  
type: talk

abstract: >
  For decades, distributed systems researchers have treated synchrony as an unrealistic assumption. After all, how can a protocol rely on timing guarantees in a world of unpredictable networks and arbitrary delays? But what if this conventional wisdom no longer holds?
  In this talk, I will revisit one of the oldest assumptions in distributed computing through the lens of modern public clouds. Drawing on an extensive measurement study across multiple cloud providers and geographic regions, I will show that communication delays are often far more predictable than commonly believed, particularly for small messages.
  Motivated by these findings, I will explore what becomes possible when synchrony is treated not as a theoretical convenience, but as a practical design tool. I will illustrate these ideas with SyncPaxos, a synchronous variant of Paxos, along with several extensions that exploit characteristics of public cloud infrastructures. We will examine their performance, their robustness to timing violations, and the trade-offs they make compared to traditional partially synchronous approaches.
  The talk will argue that synchrony is not a relic of textbook models, but an increasingly practical foundation for cloud-scale distributed systems. Beyond improving performance, synchronous protocols can reduce protocol complexity, eliminate costly recovery mechanisms, and enable more resource-efficient replication. In this sense, synchrony may offer a path toward not only faster but also more sustainable distributed systems.
---
