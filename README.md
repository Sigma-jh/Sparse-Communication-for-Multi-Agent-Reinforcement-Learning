# Adaptive Sparse Communication for Multi-Agent Reinforcement Learning

This repository provides the official implementation of our paper:

**"Sparse Communication for Policy Shaping in Multi-Agent Reinforcement
Learning"**

## Overview

We propose a communication framework for cooperative multi-agent deep reinforcement learning under partial observability. The method introduces a **threshold-gated communication mechanism** that adaptively controls information exchange based on spatial and vector observations.

Built on a communication-aware QMIX architecture, our approach combines:
- Sparse neighbor-based communication
- Attention-based message aggregation
- Threshold-controlled communication triggering

## Key Features

- 🔹 Adaptive communication via threshold gating  
- 🔹 Reduced communication overhead without performance loss  
- 🔹 Improved coordination behaviors (focus-fire, formation, micro-control)  
- 🔹 Compatible with multiple MARL backbones  

## Results

Our method is evaluated on the **StarCraft Multi-Agent Challenge (SMAC)** benchmark and demonstrates:

- Comparable or improved win rates vs QMIX  
- Reduced communication frequency  
- Distinct coordination strategies under different sparsity levels  

