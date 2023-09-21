<p  align="center"> بسم الله الرحمن الرحيم</p>

<p align="center">
  <img src="https://fontmeme.com/permalink/220326/f0317afa6de04ad1c83003645b98179d.png">
</p>

<p align="center">
A Computer Science Curriculum with Rust flavor!
</p>

<p align="center">
<a href="https://github.com/rust-unofficial/awesome-rust">
  <img src="https://awesome.re/mentioned-badge-flat.svg" alt="Awesome">
</a>
</p>

```rust
// tl:dr
let RustyCS = CS.iter().zip(Rust.iter())
```

# Contents

- [Contents](#contents)
- [Why Learn Computer Science](#why-learn-computer-science)
- [Why Learn Rust](#why-learn-rust)
- [Why This Curriculum](#why-this-curriculum)
- [How To Use](#how-to-use)
- [Contribution and Community](#contribution-and-community)
- [Acknowledgment](#acknowledgment)
- [Curriculum](#curriculum)
  - [Prerequisites](#prerequisites)
  - [Introduction](#introduction)
  - [Programming Languages](#programming-languages)
  - [Discrete Structures](#discrete-structures)
  - [Systems Fundamentals](#systems-fundamentals)
  - [Algorithms](#algorithms)
  - [Architecture and Organization](#architecture-and-organization)
  - [CS Tools](#cs-tools)
  - [Information Management](#information-management)
  - [Networking and Communications](#networking-and-communications)
  - [Operating Systems](#operating-systems)
  - [Distributed Computing and Advanced Databases](#distributed-computing-and-advanced-databases)
  - [Compilers and Interpreters](#compilers-and-interpreters)
  - [Information Assurance and Security](#information-assurance-and-security)
  - [Software Engineering](#software-engineering)
- [Rust Handy references](#rust-handy-references)
  - [Managing your project](#managing-your-project)
- [Blogs](#blogs)
- [Channels](#channels)
- [Rust Community](#rust-community)
- [Jobs](#jobs)

# Why Learn Computer Science

From Teachyourselfcs.com:

> There are 2 types of software engineer: those who understand computer science well enough to do challenging, innovative work, and those who just get by because they’re familiar with a few high level tools.
> Both call themselves software engineers, and both tend to earn similar salaries in their early careers. But Type 1 engineers progress toward more fulfilling and well-remunerated work over time, whether that’s valuable commercial work or breakthrough open-source projects, technical leadership or high-quality individual contributions.
> Type 1 engineers find ways to learn computer science in depth, whether through conventional means or by relentlessly learning throughout their careers. Type 2 engineers typically stay at the surface, learning specific tools and technologies rather than their underlying foundations, only picking up new skills when the winds of technical fashion change.
> Currently, the number of people entering the industry is rapidly increasing, while the number of CS grads is relatively static. This oversupply of Type 2 engineers is starting to reduce their employment opportunities and keep them out of the industry’s more fulfilling work. Whether you’re striving to become a Type 1 engineer or simply looking for more job security, learning computer science is the only reliable path.

# Why Learn Rust

There are a lot of reasons why one would want to learn Rust, but I'm going to mention just what I think are the killer features:
Rust is a low-level programming language with direct access to hardware and memory, giving you the same power that C and C++ do with a greater focus on memory safety. Rust also makes it easier to write concurrent programs by preventing data races at compile time.
Another great thing about Rust is that Rust is a low-level language with abstractions from higher-level languages without any performance sacrifices (zero-cost abstraction).
Rust is general-purpose and can be used for almost anything from embedded systems, building operating systems to running on the browser via webassembly. The possibilities are endless.

# Why This Curriculum

At first, I made a CS curriculum based on the [ACM & IEEE Computer Science Curricula 2013 guidelines](https://www.acm.org/binaries/content/assets/education/cs2013_web_final.pdf) to make up for the low learning quality in the university where I study. Then I found out about Rust and fell in love with it. I wanted to jump in right away, but I had my CS courses to finish first, later I had this idea about spreading some Rust over my CS curriculum, this way I can learn them both at the same time, plus Rust being a system programming language it's almost imperative to have a strong CS background first before you can use it effectively.

# How To Use

This is a Computer Science curriculum first and foremost, <del>designed to mimic an undergraduate Computer Science degree</del> focused on systems programming and provides high-quality learning content from top-notch universities adhering to the [ACM & IEEE Computer Science Curricula 2013 guidelines](https://www.acm.org/binaries/content/assets/education/cs2013_web_final.pdf).

You may follow this curriculum even if you are not interested in learning Rust by skipping Rust sections. For those who are here to learn both CS and Rust, the way to go is to study the material in the given order. Each section contains the academic course(s) and the relevant Rust implementation(s). you start with the academic part and then move to the applicative Rust part if found.

**Make sure that you satisfy the prerequisites before starting any course.**

# Contribution and Community

Everyone is welcome to contribute to this curriculum. For broken/missing links, spelling errors, and language refactoring, please create a pull request with the fixes. If you think that there is an issue with the curriculum, like missing or wrong prerequisites, wrong order of courses, inaccurate or a better description of courses and sections, better alternatives to the suggested courses, please open an issue stating what's wrong and your suggestion to fix it.

# Acknowledgment

Although this was an original idea, I consider The [OSSU](https://github.com/ossu/computer-science/) and [Teachyourselfcs](https://teachyourselfcs.com) curriculums prior arts. This project borrowed a lot from them in terms of courses recommendations and organizations, even quotes. Many thanks to them.

# Curriculum

## Prerequisites

The below material assumes that you have already finished high school. If not, you can study the needed math and physics course at [Khan Academy](https://www.khanacademy.org/). Additionally, some courses require Calculus as a prerequisite. You can either go through the courses and learn the required calculus part when needed or take a complete calculus course such as the one on [Khan Academy](https://www.khanacademy.org/) or [MIT-Open Learning Library](https://openlearning.mit.edu/courses-programs/open-learning-library?f%5B0%5D=open_moocs_departments%3A29).

Additionally, the curriculum starts with How to Code courses as introductory courses. These courses may be somewhat challenging. Initially, the curriculum suggested starting with [Python for Everybody](https://www.py4e.com/) but later removed to reduce the number of introductory materials, and the idea of learning python where comers expect to learn Rust may be unappealing to most. However, feel free to take it if you struggle with these courses. It's a good starting point for those who never wrote a line of code before.

## Introduction

**CS Part:** <br>
Start here. These two courses will teach you general ways of thinking about programming and how to write programs even if you have experience. the knowledge that you will learn here will serve you forever and you will use them in literally everything.

Check these summeries to get a sneak peak of what is coming ahead in your CS journey [here](https://www.youtube.com/watch?v=-uleG_Vecis) and [here](http://carlcheo.com/compsci).

| Course name                                                                             | Associated Book                                                                   | Other Resources                      | Prerequisite            |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------ | ----------------------- |
| [How to Code Simple Data](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x)   | [How to Design Programs](https://htdp.org/)                                       | /                                    | /                       |
| [How to Code Complex Data](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) | [How to Design Programs](https://htdp.org/)                                       | /                                    | How to Code Simple Data |

**Rust Part:** <br>
After finishing the above courses, you should be able to read the book, in addition to the official book, another small book with a gentler introduction to some concepts is provided. And while you're at it, solve the exercises and questions below to help retain the knowledge.
There is no particular order to go through the materials except of course reading the book.

- [**Book**-The Rust Programming Language Book](https://doc.rust-lang.org/book/) The offcial book of the language will give you an overview of the language from first principles.
- [**Track**-Rustlings](https://github.com/rust-lang/rustlings/)
- [**Track**-Rust By Practice](https://practice.rs/)
- [**Project**-PNGme](https://picklenerd.github.io/pngme_book/introduction.html) - An Intermediate Rust Project.
- [**Project**-Triangle From Scratch](https://rust-tutorials.github.io/triangle-from-scratch/) - draw a triangle using Win32, but no external crates

## Programming Languages

In addition to learning programming languages, learning about  programming languages will benefit you tremendously.

| Course name                                                                                 | Associated Book | Other Resources                                                          | Prerequisite                 |
| ------------------------------------------------------------------------------------------- | --------------- | ------------------------------------------------------------------------ | ---------------------------- |
| [Programming Languages Part A](https://www.coursera.org/learn/programming-languages)        | /               | [Course website](https://courses.cs.washington.edu/courses/cse341/19sp/) | How to Code Complex Data     |
| [Programming Languages Part B](https://www.coursera.org/learn/programming-languages-part-b) | /               | [Course website](https://courses.cs.washington.edu/courses/cse341/19sp/) | Programming Languages Part A |
| [Programming Languages Part C](https://www.coursera.org/learn/programming-languages-part-c) | /               | [Course website](https://courses.cs.washington.edu/courses/cse341/19sp/) | Programming Languages Part B |

## Discrete Structures

**CS Part:** <br>

This course covers the most important parts of mathematics relevant to Computer Science, which are needed later in areas like Algorithms and Sytems studies. My official recommendation is Discrete Mathematics with Applications by Susanna S. Epp, it provides a gentler introduction, and the material is explained in a very good way. Sadly the book is not free. As an alternative, you can work through the Trefor Bazett course on Youtube, it has decent quality and is accompanied by a free book. Make sure to check How to Solve it book, a unique guide to general problem solving.
| Course name                                                                                                       | Associated Book                                                                                          | Other Resources                                                                                                                                                                                                                                                                                                  | Prerequisite |
| ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| [Discrete Mathematics with Applications](https://www.amazon.com/gp/product/B07M87BWRC/) | / | - [Extremely summarized study guide discrete math](https://github.com/jongwoojeff/DiscreteMathematics/wiki) <br> - [How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/) | /            |
| [Discrete Mathematics - Trefor Bazett](https://www.youtube.com/watch?v=rdXw7Ps9vxc&list=PLHXZ9OQGMqxersk8fUxiUMSIx0DBqsKZS) | [Discrete Mathematics: An Open Introduction](http://discrete.openmathbooks.org/dmoi3/dmoi.html) | / | /            |

**Rust part:**<br>
These resources are not related to this section, but they are included here to keep your memory sharp and to be able to switch between doing the course and practicing Rust so you don't get bored.

- [**Track**-Rust Exercism](https://exercism.org/tracks/rust)
- [**Track**-Rust Practice Questions](https://rust-unofficial.github.io/rust-practise-questions/)
- [**Project**-Build your own JIRA with Rust](https://github.com/LukeMathWalker/build-your-own-jira-with-rust/) - A test-driven workshop to learn Rust building your own JIRA clone!
- [**Book**-Rust Programming by Example](https://www.amazon.com/Rust-Programming-Example-concurrent-applications/dp/1788390636)
- [**Book**-Creative Projects for Rust Programmers](https://www.packtpub.com/programming/creative-projects-for-rust-programmers)

## Systems Fundamentals

**CS Part:** <br>

The best course to learn how computers work and how to build one. This course will prepare you for the upcoming courses about computer architectures and operating systems.

| Course name                                                                                             | Associated Book                                                                                | Other Resources                                | Prerequisite                                         |
| ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------- | ---------------------------------------------------- |
| [Build a Modern Computer from First Principles Part 1](https://www.coursera.org/learn/build-a-computer) | [The Elements of Computing Systems](https://mitpress.mit.edu/books/elements-computing-systems) | [Course website](https://www.nand2tetris.org/) | Up to Chapter three of Discrete Math with Applications                                                   |
| [Build a Modern Computer from First Principles Part 2](https://www.coursera.org/learn/nand2tetris2)     | [The Elements of Computing Systems](https://mitpress.mit.edu/books/elements-computing-systems) | [Course website](https://www.nand2tetris.org/) | - Build a Modern Computer from First Principles Part 1 <br> - Good with at least one programming language (Rust, Java, Python...) |

## Algorithms

**CS part:**<br>
Familiarity with common algorithms and data structures is one of the most empowering aspects of a computer science education. This is also a great place to train one’s general problem-solving abilities, which will pay off in every other area of study. How to Solve it book will also be usefull here.

| Course name                                                                                                                                                | Associated Book                                                                                                 | Other Resources                                                                                  | Prerequisite                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- |
| [Algorithms](https://www.coursera.org/specializations/algorithms) | [Algorithms Illuminated](http://www.algorithmsilluminated.org/) | [VisuAlgo](https://visualgo.net/en) visualizing data structures and algorithms through animation | - Discrete Mathematics |

**Rust part:**<br>
Solving problems with the language that you are trying to learn is the best way to learn it. Go ahead and solve as most as you can. Check more problems at leetcode.com, Hackerrank, Codewars, etc...

- [**Book**-Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust)
- [**Repo**-Rust Gym: Leetcode, AoC, Googe..](https://github.com/warycat/rustgym)
- [**Playlist**-Rust Advent of Code 2019](https://www.youtube.com/playlist?list=PLQXBtq4j4Ozkx3r4eoMstdkkOG98qpBfg) - Brian Myers
- [**Repo**-ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust)
- [**Repo**-Algorithm Cookbook in Rust](https://github.com/EbTech/rust-algorithms)
- [**Book**-Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html)

## Architecture and Organization

Learning what is going on under the hood of a computer system is what makes the difference between a programmer and a good programmer. Understand computer systems will let you write faster, more efficient and more reliable software.

| Course name                                                                                                                                          | Associated Book                                                          | Other Resources | Prerequisite                                         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | --------------- | ---------------------------------------------------- |
| [CMU 15-213: Introduction to Computer Systems](https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/schedule.html)                                         | [Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/) | /               | - Build a Modern Computer from First Principles Part 2 <br> - C language |

## CS Tools

**CS part:**<br>
This course will teach you the general tools that you may need and make it easier for you to create programs like the shell and Git.

| Course name                                                                             | Associated Book                                                                   | Other Resources                      | Prerequisite            |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------ | ----------------------- |
| [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)             | /                                                                                 | /                                    | /                       |

**Rust Part:** <br>
These resources are not related to this section, but they are included here to keep your memory sharp and to be able to switch between doing the course and practicing Rust so you don't get bored.

- [Rust Quiz](https://dtolnay.github.io/rust-quiz/14)

## Information Management

It's necessary to learn how databases work. You will find yourself dealing with them in almost all fields of programming. Don't be intimidated by the number of courses, they are short.

| Course name                                                                                   | Associated Book                                                                 | Other Resources                                                                                                                                     | Prerequisite                                                   |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [Databases: Modeling and Theory](https://www.edx.org/course/modeling-and-theory)              |                              /                                                  |                                        /                                                                                                            |                                          /                     |
| [Databases: Relational Databases and SQL](https://www.edx.org/course/databases-5-sql)             |                              /                                                  |                                        /                                                                                                            |                                          /                     |
| [Databases: Advanced Topics in SQL](https://www.edx.org/course/advanced-topics-in-sql)           |                              /                                                  |                                        /                                                                                                            |                                          /                     |
| [Databases: Semistructured Data](https://www.edx.org/course/semistructured-data)             |                              /                                                  |                                        /                                                                                                            |                                          /                     |

## Networking and Communications

**CS part:**<br>
From teachyourselfcs.com: Given that so much of software engineering is on web servers and clients, one of the most immediately valuable areas of computer science is computer networking. Our self-taught students who methodically study networking find that they finally understand terms, concepts and protocols they’d been surrounded by for years.

| Course name                                                                                    | Associated Book                                                                             | Other Resources                                                      | Prerequisite      |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | ----------------- |
| [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/lectures.php) | [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/index.php) | -[Beej's Guide to Network Programming](https://beej.us/guide/bgnet/) | Good in at least one: C, Python,  Java  |

**Rust part:**<br>
A reimplementation of what you learned about networks in Rust. This will be of great value in your future projects.

- [**Course**-TIKV Practical Networked Applications in Rust](https://github.com/pingcap/talent-plan/tree/master/courses/rust)
- [**Book**-Network Programming with Rust](https://www.oreilly.com/library/view/network-programming-with/9781788624893/)
- [**Project**-Building a DNS server in Rust](https://github.com/EmilHernvall/dnsguide)
- [**Course**-Low-Level Academy](https://lowlvl.org/)


## Operating Systems

**CS part:**<br>
So what happens when a program runs?

| Course name                                                                                   | Associated Book                                                                 | Other Resources                                                                                                                                     | Prerequisite                                                   |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [Introduction to Operating Systems](https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/) | [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) | [This](https://github.com/ossu/computer-science/tree/master/coursepages/ostep) Extensive guide from [OSSU](https://github.com/ossu/computer-science) wirtten by [palladian1](https://github.com/palladian1) will show you how to effectively take this course, make sure to read it! | - Introduction to Computer Systems<br> - C language              |

**Rust part:**<br>

- [**Book**-Rust in Action](https://www.manning.com/books/rust-in-action)
- [**Blog**-Writing a file system from scratch in Rust](https://blog.carlosgaldino.com/writing-a-file-system-from-scratch-in-rust.html)
- [**Blog Series**-Writing an OS in Rust](https://os.phil-opp.com/)
- [**Book**-The Theseus OS Book](https://www.theseus-os.com/Theseus/book/index.html)
- [**News Letter**-OSDev,Operating System Development in Rust](https://rust-osdev.com/)
- [**Book**-intermezzOS OS](http://intermezzos.github.io/book/second-edition/)


## Distributed Computing and Advanced Databases

**CS part:**<br>
“It’s typical now for even very small applications to run across multiple machines. Distributed systems is the study of how to reason about the trade-offs involved in doing so.”

| Course name                                                                             | Associated Book                                                     | Other Resources                                                                                        | Prerequisite                                   |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------- |
| [CMU 15-445: Intro to Database Systems](https://15445.courses.cs.cmu.edu/)              | [Database System Concepts 7th ed](https://www.db-book.com/)         |                                      /                                                                 | - Introduction to Computer Systems <br> - C++  |
| [Distributed Systems MIT 6.824](https://pdos.csail.mit.edu/6.824/)                      |                                        /                            |                                      /                                                                 | Operating Systems and networking and databases |
| [Designing Data-Intensive Applications](https://dataintensive.net/)                     |                                       /                             | [Author Website](https://martin.kleppmann.com/2020/11/18/distributed-systems-and-elliptic-curves.html) |                                                |


**Rust part:**<br>

- [**Book**-Async Raft](https://async-raft.github.io/async-raft/) - the Raft distributed consensus protocol in async Rust
- [TIKV Training program in Distributed Systems](https://tikv.org/blog/talent-training/)  this course focuses on implementing important distributed algorithms, including the Raft consensus algorithm, and the Percolator distributed transaction protocol.

## Compilers and Interpreters

“If you don't know how compilers work, then you don't know how computers work”. The first two courses cover the same topic, choose one.
**CS part:**<br>

| Course name                                                                                             | Associated Book                                                                                                                                                                                                                                                | Other Resources                                                                                                                                        | Prerequisite                     |
| ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------- |
| [Crafting interpreters](https://craftinginterpreters.com/)                                              | /                                                                                                                                                                                                                                                              | /                                                                                                                                                      | /                                |
| [Compilers](https://www.edx.org/course/compilers)                                                       | [Compilers: Principles, Techniques & Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)                                                                                                                                  | /                                                                                                                                                      | /                                |

**Rust part:**<br>

- [**Playlist**-Rust Ports of Carfting interpreters](https://www.youtube.com/playlist?list=PLib6-zlkjfXluRjBgK8grQH2IUSZjn-YN)
- [**Project**-Writing Interpreters in Rust: a Guide](https://rust-hosted-langs.github.io/book/introduction.html#writing-interpreters-in-rust-a-guide)
- [**Project**-Make a Lisp](https://github.com/kanaka/mal) - Joel Martin
- [**Project**-Cross-platform Brainfuck Interpreter implementation in Rust](https://rtoch.com/posts/brainfuck-interpreter-implementation-part-1/)
- [**Blog Series**-Why and how we wrote a compiler in Rust](https://bnjjj.medium.com/why-and-how-we-wrote-a-compiler-in-rust-blog-post-series-1-x-the-context-e2f83b10edb9)
- [**Project**-Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
- [Intro to the Architecture of LLVM](https://www.reddit.com/r/LLVM/comments/i7dy2a/intro_to_the_architecture_of_llvm/)

## Information Assurance and Security

```rust
todo()! //Inshallah
```

## Software Engineering

```rust
todo()! //Inshallah
```

# Rust Handy references

These are useful resources but are not meant to be read cover to cover. Instead, use them every time you are developing a project. you'll find references for some features that you may have a hard time understanding or help you when you are wondering what's the best way to read a file or parse an argument.

- **Cheat Sheets:**
  - [Rust Cheat Sheet](https://cheats.rs/)
  - [Another Cheat sheet](https://www.breakdown-notes.com/make/load/rust_cs_canvas)
  - [Rust Types Methods Cheat sheet](https://upsuper.github.io/rust-cheatsheet/)
  - [Another Rust Types Methods Cheat sheet](http://phaiax.github.io/rust-cheatsheet/)
  - [The Periodic Table of Rust Types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/)
  - [Rust Ownership Cheat sheet](https://github.com/kmcallister/rustic-symmetries/blob/master/README.md#rustic-symmetries)
  - [Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html)
  - [Rust Container Cheat Sheet](https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/edit#slide=id.p)
- **References:**
  - [**Book**-Rust for Rustaceans](https://nostarch.com/rust-rustaceans) -   Covers how to design reliable, idiomatic, and ergonomic Rust programs based on best principles.
  - [**Book**-Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)
  - [Official Ressources](https://www.rust-lang.org/learn)
    - [Standard Library](https://doc.rust-lang.org/std)
    - [Cargo Book](https://doc.rust-lang.org/cargo/index.html)
    - [Rust doc Book](https://doc.rust-lang.org/rustdoc/index.html)
    - [Rustc Book](https://doc.rust-lang.org/rustc/index.html)
    - [Clippy](https://github.com/rust-lang/rust-clippy)
    - [Compiler Error Index](https://doc.rust-lang.org/error-index.html)
    - [The Rust Reference](https://doc.rust-lang.org/reference/introduction.html)
- **Guidelines and Idioms:**
  - [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/) A community driven collection of example code which follow Rust best practices.
  - [Rust Cook Book](https://rust-lang-nursery.github.io/rust-cookbook/) a collection of simple examples that demonstrate good practices to accomplish common programming tasks.
  - [Rust API guidelines](https://rust-lang.github.io/api-guidelines/) An extensive list of recommendations for idiomatic Rust APIs.
  - [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)  A catalogue of design patterns in Rust.
  - [Effective Rust](https://www.lurklurk.org/effective-rust/) - Rust guidelines
  - [Rust Programming Tipz](https://github.com/ferrous-systems/elements-of-rust) A collection of software engineering techniques for effectively expressing intent with Rust.
  - [The Rust Performance Book](https://nnethercote.github.io/perf-book/title-page.html#the-rust-performance-book)
  - [Secure Rust Guidelines](https://anssi-fr.github.io/rust-guide/01_introduction.html)
  - [stdx:  Learn these crates first as an extension to std](https://github.com/brson/stdx)
  - [Common Newbie Mistakes and Bad Practices in Rust: Bad Habits](https://adventures.michaelfbryan.com/posts/rust-best-practices/bad-habits)
  - [Hexagonal architecture in Rust](https://alexis-lozano.com/hexagonal-architecture-in-rust-1/)
- **Debugging:**
  - [explaine.rs](https://jrvidal.github.io/explaine.rs/)
  - [Compiler Explorer](https://rust.godbolt.org/)
  - [Pernos](https://pernos.co/)  [demo](https://www.youtube.com/watch?v=uTc7KCBbVFI&t=162s)
- **Compiling**
  - [How to speed up the Rust compiler in March 2023](https://nnethercote.github.io/2023/03/24/how-to-speed-up-the-rust-compiler-in-march-2023.html)
  - [rust-cross, Everything you need to know about cross compiling Rust programs!](https://github.com/japaric/rust-cross) - [Jorge Aparicio](https://github.com/japaric)
- **Benchmark and Fuzzing:**
  - [Benchmarking programs in Rust](https://stackoverflow.com/questions/13322479/benchmarking-programs-in-rust)
  - [Criterion.rs](https://github.com/bheisler/criterion.rs) Benchmark
  - [Rust verification tools](https://alastairreid.github.io/rust-verification-tools/)
  - [Rust Fuzz Book](https://rust-fuzz.github.io/book/) Fuzz testing
- **Cargo:**
  - [Most useful Rust cargo tools](https://www.reddit.com/r/rust/comments/u6qrbd/comment/i5b9wv3/?utm_source=reddit&utm_medium=web2x&context=3)
- **Tools:**
  - [Awesome Rust: Development Tools](https://github.com/rust-unofficial/awesome-rust#development-tools)
  - [Awesome Rust: Libraries](https://github.com/rust-unofficial/awesome-rust#libraries)
  - [Caniuse.rs - Rust feature search](https://caniuse.rs/)
- **CI/CD:**
  - [Great Rust CI](https://dev.to/cad97/great-rust-ci-1fk6)

## Managing your project

- [Keeping Rust projects' README.md code examples up-to-date](https://blog.guillaume-gomez.fr/articles/2019-04-13+Keeping+Rust+projects%27+README.md+code+examples+up-to-date)
- [Guide on how to write documentation for a Rust crate](https://blog.guillaume-gomez.fr/articles/2020-03-12+Guide+on+how+to+write+documentation+for+a+Rust+crate) - Writing good documentation with rustdoc including many examples.
- **Building an open source project?**
  - [TP 101: Introduction to open source software](https://github.com/pingcap/talent-plan/blob/master/courses/tp101-intro-to-oss.md)
  - [TP 102: How to use Git and GitHub](https://github.com/pingcap/talent-plan/blob/master/courses/tp102-how-to-use-git-github.md)
  - [TP 103: Build a welcoming community](https://github.com/pingcap/talent-plan/blob/master/courses/tp103-open-source-community.md)


# Blogs

- [Home – Read Rust](https://readrust.net/)
- [Hackr.io: most upvoted Rust ressources](https://hackr.io/tutorials/learn-rust?sort=upvotes)
- [Morioh](https://morioh.com/topic/rust)
- [Awesome Rust, A curated list of Rust code and resources.](https://github.com/rust-unofficial/awesome-rust)
- [Idiomatic Rust](https://github.com/mre/idiomatic-rust)
- [AreWeRustYet](https://github.com/UgurcanAkkok/AreWeRustYet)
- [Lobsters.rs](https://lobste.rs/)
- [Rust official Blog](https://blog.rust-lang.org/)
- [This Week in Rust](https://this-week-in-rust.org/)
- [Dev.to Rust](https://dev.to/t/rust)
- [Llogiq on stuff](https://llogiq.github.io/)
- [Niko Matsakis](http://smallcultfollowing.com/babysteps/)
- [Endler](https://endler.dev/)
- [Lucas Palmieri](https://www.lpalmieri.com/)
- [Michael Gattozzi](https://blog.mgattozzi.dev/)
- [MICHAEL-F-BRYAN](https://adventures.michaelfbryan.com/)
- [Faster Than Lime](http://fasterthanli.me)
- [Ralf's Ramblings (ralfj.de)](https://www.ralfj.de/blog/)
- [Antoyo's Blog](https://blog.antoyo.xyz/)
- [Blogs - Without boats, dreams dry up](https://without.boats/blog/)
- [Sylvain Kerkour](https://kerkour.com/)
- [matklad](https://matklad.github.io/)
- [Yoshua Wuyts](https://blog.yoshuawuyts.com/)
- [Possible Rust](https://www.possiblerust.com/) A blog for intermediate Rust programmers exploring real-world code and design patterns.

# Channels

- [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming)
- [Manning Publications Rust channel](https://www.youtube.com/c/ManningPublications/search?query=rust)
- [Gamozolabs](https://www.youtube.com/c/gamozolabs/playlists)
- [Jon Gjengset](https://www.youtube.com/c/JonGjengset/)


# Rust Community

- [The Rust Programming Language Forum](https://users.rust-lang.org/)
- [Stackoverflow Rust questions](https://stackoverflow.com/questions/tagged/rust)
- [Rust Mentors](https://rustbeginners.github.io/awesome-rust-mentors/)
- [Rustacean Station](https://rustacean-station.org/)
- [Rust-Saar](https://rust.saarland/)
- [Rust Programming Language Community Discord Server](https://discord.gg/rust-lang-community)
- [Rust Programming Language Official Discord Server](https://discord.com/invite/rust-lang)
- [Rustacean Station Discord Server](https://discord.gg/ZFbGFF9T3J)
- [Rust بالعربي Discord Server](https://discord.gg/UFFcsKsDx4)
- [zulip chat](https://rust-lang.zulipchat.com/)

# Jobs

- [RustJobs](https://rustjobs.dev/)
- [Companies that use Rust](https://www.rust-lang.org/production/users)
