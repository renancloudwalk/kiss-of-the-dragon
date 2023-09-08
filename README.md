# Kiss Of The Dragon: Advanced Distributed Systems Challenge

**Kiss Of The Dragon** is an extension of the renowned [Maelstrom](https://github.com/jepsen-io/maelstrom/) challenge, pushing you to explore deeper realms of distributed systems. This challenge expects not only the utilization of Maelstrom's innovative testing capabilities but also necessitates the design and implementation of your own distributed nodes.

## Introduction

While Maelstrom introduced a unique workbench for understanding distributed systems, **Kiss Of The Dragon** takes another step. Here, instead of working with pre-configured nodes, you'll be diving deep into creating, testing, and optimizing your own nodes and protocols.

## Challenges

### 1. [Setup](doc/01-getting-ready/index.md)

Begin with setting up your Maelstrom environment. As the foundational tool upon which this challenge is built, it's critical to get Maelstrom up and running flawlessly.

### 2. [Develop the Protocol/Nodes Service](doc/02-protocol/index.md)

Having learned from Maelstrom the importance of efficient and robust nodes, now it's your turn:

- Craft bespoke communication protocols.
- Design and establish node services.
- Develop standardized message structures, RPC semantics, and error handling.
- Emphasize efficient JSON communication between nodes using STDIN and STDOUT.

### 3. [Echo](doc/03-echo/index.md)

Echo tests, inspired by Maelstrom's methodologies, will validate your system's foundational communication capabilities. Can your nodes effectively talk to each other?

### 4. [Conflict-free Replicated Data Type (CRDT) and Gossip](doc/04-crdts/index.md)

Taking cues from Maelstrom's advanced tests, now dive deeper:

- Implement a state-of-the-art gossip protocol.
- Manage states across distributed nodes.
- Resolve conflicts, a pivotal aspect in distributed systems.

## Features

- Real-world distributed system scenarios inspired by Maelstrom's foundational principles.
- Extensive documentation, guiding you at each stage.
- Insightful visualizations detailing system interactions.
- Progressive hands-on tasks emphasizing on ground-up building and optimization.

## License
Original Maelstrom License:

> Copyright © 2017, 2020--2022 Kyle Kingsbury, Kit Patella, & Jepsen, LLC
> 
> Distributed under the Eclipse Public License either version 1.0 or (at
> your option) any later version.

