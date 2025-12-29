# Binary Entropy Collapse Model

> A deterministic binary-state simulation with injected noise, used to visualize entropy, stabilization, and collapse over time.

**What is this?**

This project is a small systems visualization / toy model that explores how a simple deterministic binary system behaves when exposed to continuous, non-linear entropy injection.

At each tick, the system:

> advances a deterministic state transition
> injects bounded noise
> attempts to stabilize toward equilibrium
> visually demonstrates when and how collapse occurs

The result is a live visualization of emergent structure vs instability.

**Why I built it**

This was built as a thinking tool! It was also my intro to Github. 
A way to reason about:

> how small entropy inputs accumulate
> how systems temporarily stabilize
> why collapse is inevitable beyond certain thresholds

It is not a production RNG and not cryptographically secure, but it is useful for intuition-building around entropy, noise, and state progression.

Core Model

Let:

S = system state
T = tick (frame)
e = bounded entropy input

ΔS = f(T) + e
As e increases relative to system constraints, stabilization fails and collapse becomes visible.

**What this can be useful for**

Visualizing entropy injection in deterministic systems
Toy-model intuition for RNG jitter and instability
Game systems & simulation thinking
Teaching or experimenting with emergent behavior

**Tech Stack**

React
Tick-based simulation loop

This project is intentionally small, visual, and exploratory.
---


Built by [`0north.eth`](https://github.com/0north-eth)  

  
**ZERO NORTH** ⦿ **ZERO NORTH**
