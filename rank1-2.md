# Knowledge Breakdown from 1 to 2

This document provides the technical references and scoring criteria necessary to achieve Level 2. Currently, the scores can only serve as qualitative references and cannot be used to determine promotion standards based on the scores.

## LV2 requires developer with `final point >= 31`.

## Score Criteria

Each item is scored and can be precise to 0.5 points, divided into score 0-4.

- Score 0: Very Unfamiliar

  Description: the developer is completely unaware or has very basic concepts.
  Explanation: the developer might know the basic definition but cannot explain its specific applications or implementation details.

- Score 1: Basic Understanding

  Description: the developer has a basic understanding, knows some basic concepts and terms, but lacks in-depth understanding and practical experience.
  Explanation: the developer can explain basic concept, but is not familiar with specific algorithms or implementation details. The developer also doesn't have practice experience in this domain.
  Example: The developers took relevant courses in university, passed the exams, but never actually wrote code hands-on.

- Score 2: Moderately Familiar

  Description: the developer has a certain understanding, can explain major algorithms and techniques, and has some practical application experience.
  Explanation: The developer can describe some common algorithms, and has applied these techniques in simple projects under someone's guidance, for example the developer worked under guide of an experienced colleague or developed a study project with a followed step-by-step tutorials.
  Example: Developers implemented Labs in university, open source tutorials like Kaleidoscope or made minor, localized changes in a medium to large-scale project

- Score 3: Proficient

  Description: the developer is very familiar with this domain, can deeply understand and apply various algorithms, and already used these techniques in complex compiler projects independently.
  Explanation: the developer can explain complex principle in detail, and has the experience of implementation and debug independently.
  Example: Developers independently designed and implemented a functional module in a compiler.

- Score 4: Expert
  Description: the developer has expert-level knowledge and experience in this domain, and has mentored others work experience.
  Explanation: the developer can not only apply existing algorithms but also propose improvements and optimization ideas, and has guided others work.
  Example: Developers guided and coached other LV2+ developers

Note: The scoring criteria must be based on past practice. For example, if a programmer believes they can work independently but has only worked under guidance, their score of that item should be 2 instead of 3.

For projects related to computer organization principles and operating system principles, "worked on" can be understood as having used this knowledge to solve practical problems, without requiring the implementation of circuits or kernels.

## Items

| Category                         | Items                                                                     | Weight | Score |
| -------------------------------- | ------------------------------------------------------------------------- | ------ | ----- |
| Compilation                      | Scanner 词法分析器                                                        | 1      |       |
|                                  | Parser 语法分析器                                                         | 1      |       |
|                                  | Context-Sensitive Analysis 上下文相关分析（语义分析）                     | 1      |       |
|                                  | Procedure Abstraction 函数调用设计 (ABI，Linker, Memory Manager)          | 1      |       |
|                                  | Code Shape 1 代码形式 1 (Arithmetic, for, if, switch)                     | 1      |       |
|                                  | Code Shape 2 代码形式 2 (Runtime Memory Layout, Object Module, Reference) | 1      |       |
|                                  | Data Flow Analysis (Domination, Fixed Point Algorithm, SSA, Call Graph)   | 1      |       |
|                                  | Instruction Select                                                        | 1      |       |
|                                  | Instruction Scheduler                                                     | 1      |       |
|                                  | Register Allocation                                                       | 1      |       |
| Computer organization principles | Instruction fetch and decoding                                            | 1      |       |
|                                  | Cache                                                                     | 1      |       |
|                                  | CPU pipeline                                                              | 1      |       |
|                                  | Instruction set architecture (ISA)                                        | 1      |       |
|                                  | ROM/Flash/Persistent storage                                              | 1      |       |
|                                  | Interrupt system                                                          | 1      |       |
|                                  | Basic concepts of parallel processing                                     | 1      |       |
|                                  | Atomic instructions                                                       | 1      |       |
| Operating System Principle       | Virtual memory and Memory hierarchy                                       | 1      |       |
|                                  | Memory allocation techniques                                              | 1      |       |
|                                  | Posix interface                                                           | 0.6    |       |
|                                  | Context switching                                                         | 1      |       |
|                                  | Characteristics of Real-Time Operating Systems                            | 1      |       |
|                                  | socket and network                                                        | 0.3    |       |
| Algorithms and Data Structures   | Stack                                                                     | 0      |       |
|                                  | Dynamic length array                                                      | 0      |       |
|                                  | Linked list                                                               | 0      |       |
|                                  | Hash table                                                                | 0      |       |
|                                  | Binary tree                                                               | 0      |       |
|                                  | Directed Acyclic Graph                                                    | 0      |       |

### How to convert score level to 100-point

1. calculate the point of each item by score

$$
\text{point} = \left( \frac{2^{\text{score}} - 1}{2^{\text{4}} - 1} \right) \times \text{weight} \times 100
$$

2. select top 10 items according to point

3. the final point is the average of top 10

$$
\text{final point} = \frac{\sum_{i=1}^{10} \text{point}_i}{10}
$$
