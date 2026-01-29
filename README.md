# Ant Farm

Distributed task execution with swarm-based coordination.

## Overview

Ant Farm implements swarm intelligence patterns for distributing work across multiple workers. Inspired by ant colony optimization algorithms.

## Features

- Task decomposition and distribution
- Worker discovery and health monitoring
- Load balancing with pheromone trails
- Fault tolerance and task reassignment

## Quick Start

```bash
uv sync
uv run ant-farm worker start
uv run ant-farm queen submit task.json
```

## License

MIT
