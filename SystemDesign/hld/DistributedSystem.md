# Distributed Systems

Distributing systems are used to solve problems.

- Computation
- Storage
- Networking

#### Elements of a Distributed System

The most important functions of distributed computing are:

- **Resource sharing** - whether it’s the hardware, software or data that can be shared
- **Openness** - how open is the software designed to be developed and shared with each other
- **Concurrency** - multiple machines can process the same function at the same time
- **Scalability** - how do the computing and processing capabilities multiply when extended to many machines
- **Fault tolerance** - how easy and quickly can failures in parts of the system be detected and recovered
- **Transparency** - how much access does one node have to locate and communicate with other nodes in the system.

#### CAP

- **Consistency** - Giving correct result at any given time
- **Availability** - System should be available at all times
- **Partition tolerance** - even if one partition fails,system should be responsive

#### Scaling in Distributed System

- Vertical
  - Adding more resources to the existing server
  - ![Vertical Scaling](/myNotes/SystemDesign/hld/Images/VerticalScaling.png)
- Horizontal
  - decentralising your server and adding more machines
  - ![Horizontal Scaling](/myNotes/SystemDesign/hld/Images/HorizontalScaling.png)

#### Links

- [Types of Distributed Systems](https://www.confluent.io/learn/distributed-systems/)
- [Design Issues](https://www.geeksforgeeks.org/design-issues-of-distributed-system/)
