<p align="center">
  <img src="https://raw.githubusercontent.com/yusufatmaca/principia-computatoria/main/assets/logo.svg" width="600">
</p>

> *"To understand the machine is to understand the mind of the maker."*

This repository serves as a personal knowledge base and a persistent digital bookshelf. It was created to archive valuable resources—articles, university courses, white papers, and manuals—that I have encountered during my career as a Computer Scientist.

The landscape of software engineering, particularly in low-level systems and high-performance computing, is vast. I created this collection primarily to safeguard these references against loss and to organize my own learning path. However, I have made it public in the hope that fellow engineers, researchers, and students traversing the same depths of computer science will find these maps useful.

## 🏛️ Philosophy
Principia Computatoria is a personal and public treatise on computing. It embraces:
- First principles thinking
- Breadth with depth across CS subfields
- Elegant, minimalist curation
- High signal, zero noise
- Longevity over trends

This is not a bookmark dump. It is a structured, evolving handbook.

## 🧭 Table of Contents
- [C/C++ and Memory Models](docs/cpp.md)
- [High-Performance Computing, Parallel Programming, CUDA, etc.](docs/hpc.md)
- [Data Structures and Algorithms](docs/dsa.md)
- Operating Systems and Computer System Architecture
- Databases & Query Optimization
- Distributed & Real-Time Systems
- Linux, Contributing Open Source, Docker
- Compilers, Automata & Parsers
- Computer Graphics
- General Computer Science
- Math, AI & ML
- Emacs
- Development Environment & .bashrc

## 📁 Repository Structure
```
principia-computatoria/
├── README.md
├── docs/
│   ├── cpp.md
│   ├── hpc.md
│   ├── ...
│   └── ...
```
Each topic lives in its own docs/*.md page.

## C/C++ & Memory Models
*References, guidelines, and deep dives into memory.*
### Manuals, References, etc.
- [C++ Best Practices](https://lefticus.gitbooks.io/cpp-best-practices/content/)
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)
- [The Pitchfork Layout](https://joholl.github.io/pitchfork-website/#intro)
- [Beej's Guides](https://beej.us/guide/)
- [Awesome C++: A collection of resources on modern C++](https://awesomecpp.com/)
- [Fluent C++](https://www.fluentcpp.com/posts/)
- [Design and Evolution of `constexpr`](https://pvs-studio.com/en/blog/posts/cpp/0909/)

### Memory & Low-Level
- [The Price of Dynamic Memory Allocation](https://johnnysswlab.com/the-price-of-dynamic-memory-allocation/)
- [Locality of Reference (Wikipedia)](https://en.wikipedia.org/wiki/Locality_of_reference)
- [Parts of Good Taste (Linus Torvalds on Linked Lists)](https://felipec.github.io/good-taste/parts/1.html)
- [FreeBSD Malloc Implementation Paper](https://docs-archive.freebsd.org/44doc/papers/malloc.pdf)
- [Visualizing Memory Allocation](https://samwho.dev/memory-allocation)
- [Enter the Arena (Arena Allocators)](https://www.rfleury.com/p/enter-the-arena-talk)
- [Pointers and Memory (MIT Reading)](https://pdos.csail.mit.edu/6.828/2014/readings/pointers.pdf)

### Practice & Assignments
- [CMU 15-445 Database Bootcamp](https://github.com/cmu-db/15445-bootcamp)
- [CS106L: Standard C++ Programming](https://web.stanford.edu/class/cs106l/)
- [Modern C++ Tutorial](https://github.com/changkun/modern-cpp-tutorial)
- [MIT 6.S096: Effective Programming in C/C++](https://ocw.mit.edu/courses/6-s096-effective-programming-in-c-and-c-january-iap-2014/)
- [Imperial College: Unit Testing in C++](https://imperialcollegelondon.github.io/unit_testing_Cpp/index.html)
- [CodeCrafters](https://codecrafters.io/)

---

## HPC, CUDA & Optimization
*Parallel programming, GPU architecture, and performance engineering.*

### Courses & Collections
- [MIT 6.172: Performance Engineering](https://ocw.mit.edu/courses/6-172-performance-engineering-of-software-systems-fall-2018/)
- [Algorithmica: HPC](https://en.algorithmica.org/hpc/)
- [Programming Parallel Computers (Aalto)](https://ppc.cs.aalto.fi)
- [Performance-Aware Programming Series](https://www.youtube.com/playlist?list=PLEMXAbCVnmY7t29i_rd3mnALWu-aZr_42)
- [GPU Mode Lectures](https://github.com/gpu-mode/lectures)

### CUDA & GPU Specific
- [NVIDIA Modern CUDA C++ Programming (YouTube Playlist)](https://www.youtube.com/playlist?list=PL5B692fm6--vWLhYPqLcEu6RF3hXjEyJr)
- [CUDA 120 Days Challenge](https://github.com/AdepojuJeremy/CUDA-120-DAYS--CHALLENGE)
- [GPU Puzzles](https://github.com/srush/GPU-Puzzles)
- [NVIDIA CCCL (C++ Standard Library for CUDA)](https://github.com/NVIDIA/cccl)
- [Matrix Multiplication Optimization (Blog)](https://siboehm.com/articles/22/CUDA-MMM)
- [Fast Matrix Multiplication from Scratch with Tensor Cores](https://alexarmbr.github.io/2024/08/10/How-To-Write-A-Fast-Matrix-Multiplication-From-Scratch-With-Tensor-Cores.html)

---

## Operating Systems & Computer Architecture
*How the machine works.*

- [OSTEP (Operating Systems: Three Easy Pieces)](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [r/osdev Wiki](https://www.reddit.com/r/osdev/)
- [Write your own Virtual Machine (LC-3)](https://www.jmeiners.com/lc3-vm/)
- [Seeing the Matrix (Coding Confessions)](https://blog.codingconfessions.com/p/seeing-the-matrix)
- [Ben Eater's Breadboard Computer Tips](https://www.reddit.com/r/beneater/comments/ii113p/helpful_tips_and_recommendations_for_ben_eaters/)

---

## Databases & Distributed Systems
*Scalability, consistency, and query engines.*

### Databases
- [CMU 15-445: Intro to Database Systems](https://15445.courses.cs.cmu.edu)
- [CMU 15-721: Advanced Database Systems](https://15721.courses.cs.cmu.edu/)
- [B-trees and Database Indexes](https://planetscale.com/blog/btrees-and-database-indexes)
- [From Web Dev to DB Dev](https://notes.eatonphil.com/2025-02-15-from-web-developer-to-database-developer-in-10-years.html)

### Distributed & Real-Time
- [MIT 6.824: Distributed Systems](https://pdos.csail.mit.edu/6.824/schedule.html)
- [Distributed Systems Reading List](https://ferd.ca/a-distributed-systems-reading-list.html)
- [DSLabs (Distributed Systems Labs)](https://github.com/emichael/dslabs)
- [Real-Time System Architecture Evolution](https://medium.com/cloud-and-servers/gerçek-zamanlı-sistem-mimarisinin-evrimi-websocketten-kafka-ya-9cc47f003633)
- [Implementing MapReduce in Golang](https://jitesh117.github.io/blog/implementing-mapreduce-in-golang/)

---

## Compilers, Parsers & Automata
*Translating code to machine instructions.*

- [LLVM Tutorial](https://llvm.org/docs/tutorial/)
- [Regular Expression Matching Can Be Simple And Fast](https://swtch.com/~rsc/regexp/)
- [Crafting Interpreters (Parsing Expressions)](https://craftinginterpreters.com/parsing-expressions.html)
- [Teeny Tiny Compiler](https://austinhenley.com/blog/teenytinycompiler1.html)
- [Reflections on Trusting Trust (Ken Thompson)](https://www.cs.cmu.edu/~rdriley/487/papers/Thompson_1984_ReflectionsonTrustingTrust.pdf)
- [A Compiler Writer's Journey](https://github.com/DoctorWkt/acwj)
- [ANTLR](https://www.antlr.org/)

---

## Data Structures and Algorithms
*Foundational knowledge.*

- [MIT 6.851: Advanced Data Structures](https://courses.csail.mit.edu/6.851)
- [Visualgo (Visualizing Data Structures)](https://visualgo.net/en)
- [CS Primer](https://csprimer.com/courses/)
- [Nand2Tetris](https://www.nand2tetris.org/)
- [Lamport's "How to Write a Proof"](https://lamport.azurewebsites.net/pubs/howto.txt)
- [Computer Graphics from Scratch](https://gabrielgambetta.com/computer-graphics-from-scratch/)

---

## Development Environment (Linux, Git, Emacs)
*Tools of the trade.*

### Linux & Shell
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [Grep by Example](https://antonz.org/grep-by-example/)
- [Fast Pipes](https://mazzo.li/posts/fast-pipes.html)
- [pwn.college: Linux Luminarium](https://pwn.college/login?next=/linux-luminarium/terminal-multiplexing/)

### Git
- [Think Like (a) Git](https://think-like-a-git.net/)
- [Oh Shit, Git!?!](https://ohshitgit.com/)
- [Learn Git Branching](https://learngitbranching.js.org/)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Emacs
- [Emacs From Scratch (System Crafters)](https://www.youtube.com/playlist?list=PLEoMzSkcN8oPH1au7H6B7bBJ4ZO7BXjSZ)
- [Emacs C++ LSP Guide](https://emacs-lsp.github.io/lsp-mode/tutorials/CPP-guide/)
- [Doom Emacs](https://github.com/doomemacs/doomemacs)
- [Purcell's emacs.d](https://github.com/purcell/emacs.d)

### Docker
- [Docker Advance Training Exercises](https://github.com/kratochj/docker-advance-training-exercise/tree/master)

---

## Blogs & Reading List
- [Netflix Tech Blog](https://netflixtechblog.com/)
- [Cloudflare Blog](https://blog.cloudflare.com/)
- [Engineering at Meta](https://engineering.fb.com/)
- [Ben Kuhn](https://www.benkuhn.net/progessays/)
- [Eaton Phil](https://eatonphil.com/blogs.html)
- [Stephen Diehl](https://www.stephendiehl.com/)
- [Mostly Nerdless](https://mostlynerdless.de/)

---

### Minimalist Web
- [No CSS Club](https://nocss.club/)
- [1MB Club](https://1mb.club/)
