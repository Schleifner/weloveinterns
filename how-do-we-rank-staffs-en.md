# How We Evaluate Developers' Skill Levels

We classify abilities into six different levels, from LV0 to LV5. Upon reaching different ability levels, individuals possess corresponding skills and take on appropriate responsibilities. The ability level evaluation is determined through multiple rounds of voting using the [Delphi technique](https://www.knowledgehut.com/blog/project-management/delphi-technique-in-pmp) by current maintainers and the line manager. **Ratings must be conducted level by level, and skipping levels is not allowed**. In particular, individuals lacking technical skills are not permitted to skip LV2 and be promoted to LV3+.

## LV5

- Based on LV4, capable of independently analyzing and breaking down problems, integrating various resources to complete tasks.
- Able to guide LV4 and below partners, independently lead the development team, and ensure delivery.
- Capable of handling various emergencies and communicating with the line manager on behalf of the team.
- Has an in-depth understanding of the company's WebAssembly technology and can assist stakeholders in continuous improvement.

LV5 will be granted maintainer privileges.

## LV4

- Based on LV3, able to independently undertake module-level development work, and quickly learn new domain knowledge.
- **For large software systems like LLVM, able to independently complete debugging, error analysis, find the root cause of problems, and fix them, ensuring the timely progress of development tasks.**
- Able to guide LV3 and below partners, assisting them in completing development tasks.
- Able to independently create technical reports and share knowledge.
- Able to detect and point out errors and knowledge blind spots of LV4 and above, and correct the errors.
- **Able to independently open up a new knowledge domain for the team from scratch, supporting a specific technical direction through research reports, technical sharing, and extended development.**

LV4 can be considered as a key candidate for maintainer training.

## LV3

- Based on LV2, able to independently undertake code development work lasting more than a week.
- **Able to independently analyze encountered bugs or crashes, possessing strong testing, debugging, and error analysis capabilities.** (This is the entry threshold for LV3)
- Able to quickly understand the task's essence and find solutions with minimal mentor assistance, completing the task.
- Proficient in at C++ + Python/Typescript; C++ requires familiarity with C++14.
- Proficient in bash/python scripting languages.
- Proficient in reading English technical materials.
- Able to proficiently deliver public technical reports.

Reaching LV3 is the minimum requirement for the core dev team.

## LV2

- Based on LV1, has a systematic understanding of courses such as data structures, introduction to algorithms, computer organization principles/microcomputer principles/computer architecture, and modern database principles, has studied them, and can quickly review and master them.
- Has a good understanding and memory of the knowledge from the three courses: compiler principles, principles/microcomputer principles/computer, and modern operating systems.
- Able to independently complete all tasks in [Tiny-Wasm-Compiler-Learn](https://github.com/Schleifner/Tiny-Wasm-Compiler-Learn.git), or has equivalent **practical experience**(Note: Practical experience is not equivalent to work experience. Major assignments, course projects, experiments, etc., can also be considered as practical experience.), such as participating in or sharing technology about gcc, llvm, v8 projects.
- Proficient in using Linux command-line tools, including find, grep, sed, etc., and proficient in using different tool parameters and combinations to complete daily tasks.
- Proficient in using git for team code collaboration.
- Able to make local code changes, develop and test small features under the guidance of core dev.
- Able to proficiently complete data processing tasks using one of Python/Bash/JS languages.
- Able to debug software independently, debug own code, and use gdb.
- Knows and has used build script tools like make, cmake, can understand and modify Makefile, and can handle simple CMake configuration issues.

L2 is a necessary condition to become a compiler ecosystem developer. This level mainly requires knowledge and skills, and even part-time contributors are generally expected to reach this level. Otherwise, it is difficult to carry out the work.
More detailed calcification of Lv2 is in [rank1-2.md](./rank1-2.md)

## LV1

- Proficient in at least one programming language, must be proficient in one of C/C++/Java. (Here, "proficient" means knowing the basic concept of function calls, how to compile and run source code, and being able to write a program that reads, sorts, and outputs an array in a specified format.)
- Basic Python/Bash scripting skills. (Here, "basic" means being able to fully understand a given script through Google or books.)
- Basic Office software operation skills; able to give technical reports within the team. (New interns are required to give reports at the weekly meeting every Wednesday.)
- Able to complete function-level development under mentor guidance, read code independently, and understand local code logic.
- Capable of completing project testing, experimental data collection and cleaning, and document report writing under guidance.
- Able to communicate with mentors and colleagues as required, keep written records of work, and summarize problems and experiences.
- Experience using Linux. (This refers to command-line experience. Familiarity with common commands like grep, find, date, sed, tr, head, etc. is required.)
- Basic git and GitHub/gitlab skills. (Here, "basic" means clone, commit, push, branch, merge; GitHub operations refer to initiating PR/MR, updating PR/MR, and synchronizing with multiple remotes.)

LV1 is not able to develop Wasm compiler.

## LV0

- This is the default state for all students who have not been exposed to software development.
- Indicates no experience writing code in any programming language, and no experience using compilers.
- No concept of basic computer science knowledge such as data structures.

LV0 is not able to develop Wasm compiler.
