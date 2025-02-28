## Rating Criteria

- Rank 0: Very Unfamiliar
  1. Description: the candidate is completely unaware or has very basic concepts.
  1. Explanation: the candidate might know the basic definition but cannot explain its specific applications or implementation details.

- Rank 1: Basic Understanding
  1. Description: the candidate has a basic understanding, knows some basic concepts and terms, but lacks in-depth understanding and practical experience.
  1. Explanation: the candidate can explain basic concept, but is not familiar with specific algorithms or implementation details.

- Rank 2: Moderately Familiar
  1. Description: the candidate has a certain understanding, can explain major algorithms and techniques, and has some practical application experience.
  1. Explanation: The candidate can describe some common algorithms, and has applied these techniques in simple compiler projects under someone's guidance or followed step-by-step tutorials.

- Rank 3: Proficient
  1. Description: the candidate is very familiar with this domain, can deeply understand and apply various algorithms, and already used these techniques in complex compiler projects independently.
  1. Explanation: the candidate can explain complex algorithms in detail, and can implement and debug related issue in complex compiler project independently.

- Rank 4: Expert
  1. Description: the candidate has expert-level knowledge and experience in this domain, and has mentored others work experience.
  1. Explanation: the candidate can not only apply existing algorithms but also propose  improvements and optimization ideas, and has guided others work.

### How to convert rank level to 100-point scores

1. use 2 as the base and the rank level as the exponent to calculate the value `x`.
1. subtract 1 from this value.
1. divide the result by `2 ^ {max rank = 4} - 1`.
1. multiple by 100 to get the score.

$$
\text{score} = \left( \frac{2^{\text{rank}} - 1}{2^{\text{max rank}} - 1} \right) \times 100
$$

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

- Operating System Principle

  - Virtual memory and Memory hierarchy
  - Memory allocation techniques
  - Posix interface
  - Context switching
  - Characteristics of Real-Time Operating Systems
  - socket and network

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

### Tips

1. can apply different weighting coefficients to different items based on their importance.
1. can list the core items as needed, requiring candidates to have a rank of 2 or 2.5 or above in the core items.
