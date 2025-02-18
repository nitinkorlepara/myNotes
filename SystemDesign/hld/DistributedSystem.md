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
  - ![Vertical Scaling](/SystemDesign/hld/Images/VerticalScaling.png)
- Horizontal
  - decentralising your server and adding more machines
  - ![Horizontal Scaling](/SystemDesign/hld/Images/HorizontalScaling.png)

#### Links

- [Types of Distributed Systems](https://www.confluent.io/learn/distributed-systems/)
- [Design Issues](https://www.geeksforgeeks.org/design-issues-of-distributed-system/)
- [Dimestions of System Scalability design](https://medium.com/@Pointnity_Network/three-dimensions-of-distributed-system-scalability-design-8e0319163c8d#:~:text=Scalability%20is%20an%20important%20indicator,two%20aspects%3A%20hardware%20and%20software)
