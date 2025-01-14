# Gossip and PushSum Algorithm Simulation

This project simulates the Gossip and PushSum algorithms using the Akka framework in F#. The algorithms propagate information across nodes using different topologies, allowing for analysis of their convergence and efficiency.

## Features

- Implements Gossip and PushSum algorithms for message propagation and convergence.
- Supports multiple topologies:
  - Full Network
  - Line
  - 2D Grid
  - 3D Grid
  - Imperfect 3D Grid
- Includes neighbor creation logic tailored for each topology.
- Uses Akka Actors for parallelism and message-passing architecture.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 6.0 or later)
- [Akka.NET](https://getakka.net/) libraries
- F# development environment (e.g., Visual Studio, Rider, or VS Code)

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
