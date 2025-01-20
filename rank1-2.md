# Knowledge Breakdown from 1 to 2

This document provides the technical references and scoring criteria necessary to achieve Level 2. Currently, the scores can only serve as qualitative references and cannot be used to determine promotion standards based on the scores.

## Rating Criteria

Each item is scored and can be precise to 0.5 points, divided into four levels.

0. Completely unaware
1. No practical experience
2. Worked under someone’s guidance or followed step-by-step tutorials
3. Worked independently
4. Guided others

For projects related to computer organization principles and operating system principles, "worked on" can be understood as having used this knowledge to solve practical problems, without requiring the implementation of circuits or kernels.

## Items

- Compilation

  - Scanner 词法分析器
  - Parser 语法分析器
  - Context-Sensitive Analysis 上下文相关分析（语义分析）
  - Procedure Abstraction 函数调用设计 (ABI，Linker, Memory Manager)
  - Code Shape 1 代码形式 1 (Arithmetic, for, if, switch)
  - Code Shape 2 代码形式 2 (Runtime Memory Layout, Object Module, Reference)
  - Data Flow Analysis (Domination, Fixed Point Algorithm, SSA, Call Graph)
  <!-- - Scalar optimization (Unreachable Code, Call, etc...) -->
  - Instruction Select
  - Instruction Scheduler
  - Register Allocation

- Computer organization principles.

  - Number Systems and Encoding
  - CPU
    - ALU
    - FPU
    - Instruction fetch and decoding
    - Cache
    - CPU pipeline
    - Instruction set architecture (ISA)
  - Memory
    - RAM
    - ROM/Flash
  - Interrupt system
  - Multi-core processors
    - Basic concepts of parallel processing
    - Atomic instructions

- Operating System Principle

  - Virtual memory and Memory hierarchy
  - Memory allocation techniques
  - Posix interface
  - Context switching
  - Characteristics of Real-Time Operating Systems
  - socket and network

- Algorithms and Data Structures
  - Stack
  - Dynamic length array
  - Linked list
  - Hash table
  - Binary tree
  - Directed Acyclic Graph
