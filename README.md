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
- [Why learn Computer Science](#why-learn-computer-science)
- [Why learn Rust](#why-learn-rust)
- [Why this curriculum](#why-this-curriculum)
- [How to use](#how-to-use)
- [Contribution](#contribution)
- [Acknowledgment](#acknowledgment)
- [Curriculum](#curriculum)
  - [Prerequisites](#prerequisites)
  - [Introduction](#introduction)
  - [Systems Fundamentals](#systems-fundamentals)
  - [Discrete Structures](#discrete-structures)
  - [Algorithms 1](#algorithms-1)
  - [Programming](#programming)
  - [Programming Languages 1](#programming-languages-1)
  - [Architecture and Organization](#architecture-and-organization)
  - [Networking and Communications](#networking-and-communications)
  - [Information Management](#information-management)
  - [Algorithms 2](#algorithms-2)
  - [Operating Systems](#operating-systems)
  - [Distributed Computing](#distributed-computing)
  - [Compilers and Interpreters](#compilers-and-interpreters)
  - [Software Engineering](#software-engineering)
  - [Mathematics](#mathematics)
  - [Intelligent Systems](#intelligent-systems)
  - [Programming Languages 2](#programming-languages-2)
  - [Extra](#extra)
- [What else I can do with Rust?](#what-else-i-can-do-with-rust)
  - [CLI](#cli)
  - [Web](#web)
  - [Games](#games)
  - [Web Assembly](#web-assembly)
  - [Gui](#gui)
  - [Mobile Apps](#mobile-apps)
  - [Blockchain](#blockchain)
- [Rust Handy refrences](#rust-handy-refrences)
  - [Use While Developing your Project](#use-while-developing-your-project)
  - [Use to finalize your Project](#use-to-finalize-your-project)
- [Projects, Workshops & Live Streams](#projects-workshops--live-streams)
- [Blogs and Channels](#blogs-and-channels)
- [Rust Community](#rust-community)
- [Crates and Libs](#crates-and-libs)
- [Jobs](#jobs)
- [Sources](#sources)

# Why learn Computer Science

from Teachyourselfcs.com:

> There are 2 types of software engineer: those who understand computer science well enough to do challenging, innovative work, and those who just get by because they’re familiar with a few high level tools.
> Both call themselves software engineers, and both tend to earn similar salaries in their early careers. But Type 1 engineers progress toward more fulfilling and well-remunerated work over time, whether that’s valuable commercial work or breakthrough open-source projects, technical leadership or high-quality individual contributions.
> Type 1 engineers find ways to learn computer science in depth, whether through conventional means or by relentlessly learning throughout their careers. Type 2 engineers typically stay at the surface, learning specific tools and technologies rather than their underlying foundations, only picking up new skills when the winds of technical fashion change.
> Currently, the number of people entering the industry is rapidly increasing, while the number of CS grads is relatively static. This oversupply of Type 2 engineers is starting to reduce their employment opportunities and keep them out of the industry’s more fulfilling work. Whether you’re striving to become a Type 1 engineer or simply looking for more job security, learning computer science is the only reliable path.

# Why learn Rust

There are a lot of reasons why one would want to learn Rust, but I'm going to mention just what I think are the killer features:
Rust is a low-level programming language with direct access to hardware and memory, giving you the same power that C and C++ do with a greater focus on memory safety. Rust also makes it easier to write concurrent programs by preventing data races at compile time.
Another great thing about Rust is that Rust is a low-level language with abstractions from higher-level languages without any performance sacrifices (zero-cost abstraction).
Rust is general-purpose and can be used for almost anything from embedded systems, building operating systems to running on the browser via webassembly. The possibilities are endless.

# Why this curriculum

At first, I made a CS curriculum based on the [ACM & IEEE Computer Science Curricula 2013 guidelines](https://www.acm.org/binaries/content/assets/education/cs2013_web_final.pdf) to make up for the low learning quality in the university where I study. Then I found out about Rust and fell in love with it. I wanted to jump in right away, but I had my CS courses to finish first, later I had this idea about spreading some Rust over my CS curriculum, this way I can learn them both at the same time, plus Rust being a system programming language it's almost imperative to have a strong CS background first before you can use it effectively.

# How to use

This is a Computer Science curriculum first and foremost, designed to mimic an undergraduate Computer Science degree by providing high-quality learning content from top-notch universities adhering to the [ACM & IEEE Computer Science Curricula 2013 guidelines](https://www.acm.org/binaries/content/assets/education/cs2013_web_final.pdf). You may follow this curriculum even if you are not interested in learning Rust by skipping Rust sections.
for those who are here to learn both CS and Rust, the way to go is to study the material in the given order. Each section contains the academic course(s) and the relevant Rust implementation(s). you start with the academic part and then move to the applicative Rust part if found.
you don't have to study all the material, just what you are interested in and you think it may be useful for you of course in respect of the mentioned prerequisites.

# Contribution

Everyone is welcome to contribute to this curriculum. For broken/missing links, spelling errors, and language refactoring, please create a pull request with the fixes. If you think that there is an issue with the curriculum, like missing or wrong prerequisites, wrong order of courses, inaccurate or a better description of courses and sections, better alternatives to the suggested courses, please open an issue stating what's wrong and your suggestion to fix it.

# Acknowledgment

Although this was an original idea, I consider The [OSSU](https://github.com/ossu/computer-science/) and [Teachyourselfcs](https://teachyourselfcs.com) curriculums prior arts. This project borrowed a lot from them in terms of courses recommendations and organizations, even quotes. Many thanks to them.

# Curriculum

## Prerequisites

The below material assumes that you have already finished high school. If not, you can study the needed math and physics course at [Khan Academy](https://www.khanacademy.org/). Additionally, some courses require Calculus as a prerequisite. You can either go through the courses and learn the required calculus part when needed or take a complete calculus course such as the one on [Khan Academy](https://www.khanacademy.org/) or [MIT-Open Learning Library](https://openlearning.mit.edu/courses-programs/open-learning-library?f%5B0%5D=open_moocs_departments%3A29).

## Introduction

**CS Part:** <br>
If you have no programming background, start here. These two courses will introduce you to the world of Computer Science and give you solid fundamentals that you need to go through the curriculum and the Rust book. I would also suggest that you do some small projects with python for maximized learning.


| Course name                                                                                                                                    | Associated Book                                                                                                                                                 | Other Resources                                                                                                                                                                 | Prerequisite |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [Python for Everybody](https://www.py4e.com/)                                                                                                  | [Python for Everybody Book](https://www.py4e.com/book)                                                                                                          | [Coursera’s version](https://www.coursera.org/specializations/python)                                                                                                          | /            |
| [Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-to-computer-science-and-programming-7) | [Introduction to Computation and Programming Using Python](https://mitpress.mit.edu/books/introduction-computation-and-programming-using-python-second-edition) | [OCW’s Version](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/index.htm) | /            |

###### Awesome summaries:

[100 Computer Science Terms](https://www.youtube.com/watch?v=-uleG_Vecis)
[CS in layman terminology](http://carlcheo.com/compsci)

**Rust Part:** <br>
After finishing the above courses, you should be able to read the book, in addition to the official book, another small book with a gentler introduction to some concepts is provided. And while you're at it, solve the exercises and questions below to help retain the knowledge.
There is no particular order to go through the materials except of course reading the relevant chapter from the book before solving its exercises.
If you learn better by watching videos, you can also check the following Youtube series [Crust of Rust](https://www.youtube.com/watch?v=rAl-9HwD858&list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa).

- [**Book**-The Rust Programming Language Book](https://doc.rust-lang.org/book/) The offcial book of the language will give you an overview of the language from first principles.
- [**Book**-A Gentle Introduction To Rust](https://stevedonovan.github.io/rust-gentle-intro)
- [**Book**-Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/) A community driven collection of example code which follow Rust best practices.
- [**Track**-Rustlings](https://github.com/rust-lang/rustlings/)
- [**Book**-Rust By Practice](https://practice.rs/why-exercise.html)
- [**Book**-Rust Practise Questions](https://sn99.github.io/rust-practise-questions/) (sic)
- [Book-Easy Rust](https://dhghomon.github.io/easy_rust/Chapter_0.html) A breakdown of the rust language in the most plain english possible
- [Rust Quiz](https://dtolnay.github.io/rust-quiz/14)

## Systems Fundamentals

The best course to learn how computers work and how to build one. This course will prepare you for the upcoming courses about computer architectures and operating systems.


| Course name                                                                                             | Associated Book                                                                                | Other Resources                                | Prerequisite                                         |
| --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------------ |
| [Build a Modern Computer from First Principles Part 1](https://www.coursera.org/learn/build-a-computer) | [The Elements of Computing Systems](https://mitpress.mit.edu/books/elements-computing-systems) | [Course website](https://www.nand2tetris.org/) | /                                                    |
| [Build a Modern Computer from First Principles Part 2](https://www.coursera.org/learn/nand2tetris2)     | [The Elements of Computing Systems](https://mitpress.mit.edu/books/elements-computing-systems) | [Course website](https://www.nand2tetris.org/) | Build a Modern Computer from First Principles Part 1 |

## Discrete Structures

This course covers the most important parts of mathematics relevant to CS, which are needed later in areas like Algorithms and Sytems studies. The set of lecture notes by László Lovász did a good job of making the content approachable and intuitive, so this serves as a better starting point, then you can move to the more advanced Math for CS by MIT. Make sure to check How to Solve it book, a unique guide to general problem solving.


| Course name                                                                                                       | Associated Book                                                                                          | Other Resources                                                                                                                                                                                | Prerequisite |
| ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| [lecture notes by László Lovász](https://cims.nyu.edu/~regev/teaching/discrete_math_fall_2005/dmbook.pdf)      | /                                                                                                        | [How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)                                                                                            | /            |
| [Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about) | [Mathematics for Computer Science - Lehman, Meyer, Leighton](https://people.csail.mit.edu/meyer/mcs.pdf) | [Alternate version with solutions to the problem sets](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2005/assignments/) | /            |

## Algorithms 1

**CS part:**<br>
Familiarity with common algorithms and data structures is one of the most empowering aspects of a computer science education. This is also a great place to train one’s general problem-solving abilities, which will pay off in every other area of study. How to Solve it book will also be usefull here.


| Course name                                                                                                                                                | Associated Book                                                                                                 | Other Resources                                                                                  | Prerequisite                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [Introduction to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/index.htm) | [Introduction to algorithms 2nd ed- CLRS](https://mitpress.mit.edu/books/introduction-algorithms-third-edition) | [VisuAlgo](https://visualgo.net/en) visualizing data structures and algorithms through animation | - Introduction to Computer Science and Programming using Python.<br> - Mathematics for Computer Science. |

**Rust part:**<br>
Solving problems with the language that you are trying to learn is the best way to learn it. Go ahead and solve as most as you can. Check more problems at leetcode.com, Hackerrank, Codewars, etc...

- [**Book**-Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust)
- [**Repo**-Rust Gym: Leetcode, AoC, Googe..](https://github.com/warycat/rustgym)
- [**Repo**-Rust implementations for the Computer Language Benchmarks Game](https://github.com/TeXitoi/benchmarksgame-rs)
- [**Playlist**-Rust Advent of Code 2019](https://www.youtube.com/playlist?list=PLQXBtq4j4Ozkx3r4eoMstdkkOG98qpBfg) - Brian Myers
- [**Repo**-ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust)
- [**Repo**-Algorithm Cookbook in Rust](https://github.com/EbTech/rust-algorithms)
- [**Book**-Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html)

## Programming

**CS part:**<br>
These courses teach general ways of thinking and form neural pathways in your brain that will serve you forever and you will use them in literally everything. (quoting from [spamegg](https://github.com/spamegg1/reviews#-how-to-code-1--2) cause I couldn't find any better motivation).
And from teachyourselfcs.com about SICP :SICP is unique in its ability—at least potentially—to alter your fundamental beliefs about computers and programming. Not everybody will experience this. Some will hate the book, others won't get past the first few pages. But the potential reward makes it worth trying. while the last course will help you understand the tools that you need to make it easier for you to create programs like Git.


| Course name                                                                             | Associated Book                                                                   | Other Resources                      | Prerequisite            |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------- | ------------------------- |
| [How to Code Simple Data](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x)   | [How to Design Programs](https://htdp.org/)                                       | /                                    | /                       |
| [How to Code Complex Data](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) | [How to Design Programs](https://htdp.org/)                                       | /                                    | How to Code Simple Data |
| [Berkeley 61A](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E)       | [Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp) | [Course Website](https://cs61a.org/) | /                       |
| [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)             | /                                                                                 | /                                    | /                       |

**Rust part:**<br>
A bunch of small projects in Rust, this is officially your first step toward the Art of Programming. there is no particular order and you don't have to do all of them.

- [**Track**-Rust Exercism](https://exercism.org/tracks/rust)
- [**Book**-Rust Programming by Example](https://www.amazon.com/Rust-Programming-Example-concurrent-applications/dp/1788390636)
- [**Book**-Creative Projects for Rust Programmers](https://www.packtpub.com/programming/creative-projects-for-rust-programmers)
- [**Repo**-Build your own JIRA with Rust](https://github.com/LukeMathWalker/build-your-own-jira-with-rust/) - A test-driven workshop to learn Rust building your own JIRA clone!
- [**Book**-PNGme: An Intermediate Rust Project](https://picklenerd.github.io/pngme_book/introduction.html)
- [**Book**-Triangle From Scratch](https://rust-tutorials.github.io/triangle-from-scratch/) - draw a triangle using Win32, but no external crates
- [**Blog Series**-Hecto: Build your own text editor in Rust](https://www.philippflenker.com/hecto/)
- [**Blog**-Learning Rust through open source and live code reviews](https://loige.co/learning-rust-through-open-source-and-live-code-reviews/)
- [**Blog**-100 Rust Binary](https://www.wezm.net/v2/posts/2020/100-rust-binaries/) an example implementation of different applications in Rust.

## Programming Languages 1

You can't really be a good programmer without knowing how programming languages work.


| Course name                                                                                 | Associated Book | Other Resources                                                          | Prerequisite                 |
| --------------------------------------------------------------------------------------------- | ----------------- | -------------------------------------------------------------------------- | ------------------------------ |
| [Programming Languages Part A](https://www.coursera.org/learn/programming-languages)        | /               | [Course website](https://courses.cs.washington.edu/courses/cse341/19sp/) | How to Code Complex Data     |
| [Programming Languages Part B](https://www.coursera.org/learn/programming-languages-part-b) | /               | [Course website](https://courses.cs.washington.edu/courses/cse341/19sp/) | Programming Languages Part A |
| [Programming Languages Part C](https://www.coursera.org/learn/programming-languages-part-c) | /               | [Course website](https://courses.cs.washington.edu/courses/cse341/19sp/) | Programming Languages Part B |

## Architecture and Organization

Learning what is going on under the hood of a computer system is what makes the difference between a programmer and a good programmer. Understand computer systems will let you write faster, more efficient and more reliable software. Both courses cover the same topics. I couldn't choose which one to put in the curriculum so I did put them both, you only need to take one.


| Course name                                                                                                                                          | Associated Book                                                          | Other Resources | Prerequisite                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------ |
| [Introduction to Computer Systems](http://www.cs.cmu.edu/~213/)                                                                                      | [Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/) | /               | Build a Modern Computer from First Principles Part 2 |
| [Computation Structures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm) | /                                                                        | /               | Build a Modern Computer from First Principles Part 2 |

## Networking and Communications

**CS part:**<br>
From teachyourselfcs.com: Given that so much of software engineering is on web servers and clients, one of the most immediately valuable areas of computer science is computer networking. Our self-taught students who methodically study networking find that they finally understand terms, concepts and protocols they’d been surrounded by for years.


| Course name                                                                                    | Associated Book                                                                             | Other Resources                                                      | Prerequisite      |
| ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------- |
| [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/lectures.php) | [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/index.php) | -[Beej's Guide to Network Programming](https://beej.us/guide/bgnet/) | Some Programmming |

**Rust part:**<br>
A reimplementation of what you learned about networks in Rust. This will be of great value in your future projects.

- [**Repo**-TIKV Practical Networked Applications in Rust](https://github.com/pingcap/talent-plan/tree/master/courses/rust)
- [**Book**-Network Programming with Rust](https://www.oreilly.com/library/view/network-programming-with/9781788624893/)
- [**Repo**-Building a DNS server in Rust](https://github.com/EmilHernvall/dnsguide)
- [**Website**-Low-Level Academy](https://lowlvl.org/)

## Information Management

It's necessary to learn how databases work. You will find yourself dealing with them in almost all fields of programming.


| Course name                                                                                          | Associated Book                                                                                                                  | Other Resources                                                                                                                                                                                          | Prerequisite     |
| ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [Berkeley CS186 Introduction to Database Systems](https://www.youtube.com/user/CS186Berkeley/videos) | /                                                                                                                                | -[cs186berkeley.net](https://cs186berkeley.net/) <br>- [Architecture of a Database System (Paper)](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf) <br>- [redbook.io](http://www.redbook.io/) | Some Programming |
| Data Modeling                                                                                        | [Data and Reality: A Timeless Perspective](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215) | [Databases: Modeling and Theory](https://www.edx.org/course/modeling-and-theory)                                                                                                                         | /                |

## Algorithms 2

**CS part:**<br>
A more advanced treatment of algorithms.


| Course name                                                                                                                                                                 | Associated Book                                                                                                 | Other Resources | Prerequisite               |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ----------------- | ---------------------------- |
| [Design and Analysis of Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/index.htm) | [Introduction to algorithms 2nd ed- CLRS](https://mitpress.mit.edu/books/introduction-algorithms-third-edition) | /               | Introduction to Algorithms |

**Rust part:**<br>
solve more advanced problems from the challenges websites.

## Operating Systems

**CS part:**<br>
So what happens when a program runs?


| Course name                                                                     | Associated Book | Other Resources                                                                                                                                    | Prerequisite                                                   |
| --------------------------------------------------------------------------------- | ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) | /               | - Choose Unix kernel[book](https://pastebin.com/TBLSuvra) <br>- Do the Labs [xv6 labs](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) | Introduction to Computer Systems<br> or Computation Structures |

**Rust part:**<br>

- [**Book**-Rust in Action](https://www.manning.com/books/rust-in-action) [Repo](https://github.com/rust-in-action/code)
- [**Blog**-Writing a file system from scratch in Rust](https://blog.carlosgaldino.com/writing-a-file-system-from-scratch-in-rust.html)
- [**Blog Series**-Writing an OS in Rust](https://os.phil-opp.com/)
- [**News Letter**-OSDev,Operating System Development in Rust](https://rust-osdev.com/)
- [**Book**-intermezzOS OS](http://intermezzos.github.io/book/second-edition/)
- [**Book**-The Theseus OS Book](https://www.theseus-os.com/Theseus/book/index.html)

## Distributed Computing

**CS part:**<br>
“It’s typical now for even very small applications to run across multiple machines. Distributed systems is the study of how to reason about the trade-offs involved in doing so.”


| Course name                                                                             | Associated Book                                                     | Other Resources                                                                                        | Prerequisite                     |
| ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [Distributed Systems](https://www.cl.cam.ac.uk/teaching/2122/ConcDisSys/materials.html) | [Designing Data-Intensive Applications](https://dataintensive.net/) | [Author Website](https://martin.kleppmann.com/2020/11/18/distributed-systems-and-elliptic-curves.html) | Operating Systems and networking |

**Rust part:**<br>

- [**Book**-Async Raft](https://async-raft.github.io/async-raft/) - the Raft distributed consensus protocol in async Rust
- [TIKV Training program in Distributed Systems](https://tikv.org/blog/talent-training/)  this course focuses on implementing important distributed algorithms, including the Raft consensus algorithm, and the Percolator distributed transaction protocol.

## Compilers and Interpreters

“If you don't know how compilers work, then you don't know how computers work”. The first two courses cover the same topic, choose one.
**CS part:**<br>


| Course name                                                                                             | Associated Book                                                                                                                                                                                                                                                | Other Resources                                                                                                                                        | Prerequisite                     |
| --------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [Automata, Computability, and Complexity](https://stellar.mit.edu/S/course/6/sp15/6.045/materials.html) | -[Introduction to the Theory of Computation, Michael Sipser](https://www.amazon.com/Introduction-Theory-Computation-Michael-Sipser/dp/113318779X)<br>- [Computational Complexity: A Modern Approach, Sanjeev Aror](http://theory.cs.princeton.edu/complexity/) | [OCW Link](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-045j-automata-computability-and-complexity-spring-2011/index.htm) | Mathematics for Computer Science |
| [Theory of Computation](http://web.cecs.pdx.edu/~harry/TheoryOfComp/index.html)                         | [Introduction to the Theory of Computation, Michael Sipser](https://www.amazon.com/Introduction-Theory-Computation-Michael-Sipser/dp/113318779X)                                                                                                               | /                                                                                                                                                      | Mathematics for Computer Science |
| [Crafting interpreters](https://craftinginterpreters.com/)                                              | /                                                                                                                                                                                                                                                              | /                                                                                                                                                      | /                                |
| [Compilers](https://www.edx.org/course/compilers)                                                       | [Compilers: Principles, Techniques & Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)                                                                                                                                  | /                                                                                                                                                      | /                                |

**Rust part:**<br>

- [**Blog**-Simple but Powerful Pratt Parsing](https://matklad.github.io/2020/04/13/simple-but-powerful-pratt-parsing.html)
- [**Playlist**-Rust Ports of Carfting interpreters](https://www.youtube.com/playlist?list=PLib6-zlkjfXluRjBgK8grQH2IUSZjn-YN)
- [**Book**-Writing Interpreters in Rust: a Guide](https://rust-hosted-langs.github.io/book/introduction.html#writing-interpreters-in-rust-a-guide)
- [**Repo**-Make a Lisp](https://github.com/kanaka/mal) - Joel Martin
- [**Blog Series**-Cross-platform Brainfuck Interpreter implementation in Rust](https://rtoch.com/posts/brainfuck-interpreter-implementation-part-1/)
- [**Blog Series**-Why and how we wrote a compiler in Rust](https://bnjjj.medium.com/why-and-how-we-wrote-a-compiler-in-rust-blog-post-series-1-x-the-context-e2f83b10edb9)
- [**Blog Series**-Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
- [Intro to the Architecture of LLVM](https://www.reddit.com/r/LLVM/comments/i7dy2a/intro_to_the_architecture_of_llvm/)

## Software Engineering

TO DO Inshallah

## Mathematics

Some recommended math courses, usefull specially for people want to follow the machine learning track.


| Course name                                                                                      | Associated Book                                                                            | Other Resources                                                                                                   | Prerequisite |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------- |
| [Linear Algebra](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+18.06SC+2T2019/about) | [Introduction to Linear Algebra - Gilbert Strang](https://math.mit.edu/~gs/linearalgebra/) | [Essence of linear algebra](https://www.youtube.com/playlist?app=desktop&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | /            |
| [Probability](https://projects.iq.harvard.edu/stat110/home)                                      | [Introduction to Probability 2nd ed - Joe Blitzstein](http://probabilitybook.net/)         | /                                                                                                                 | /            |

## Intelligent Systems

**CS part:**<br>


| Course name                                                         | Associated Book                                                            | Other Resources | Prerequisite                                         |
| --------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------ |
| [Artificial intelligence](http://ai.berkeley.edu/home.html)         | [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) | /               | - Berkeley 61A<br>- Mathematics for Computer Science |
| [Machine Learning](https://www.coursera.org/learn/machine-learning) | /                                                                          | /               | /                                                    |

**Rust part:**<br>

- [Interactive tutorials on machine learning with Rust](http://learning-machines.herokuapp.com/)
- [**Repo**-End-to-end Rust ML tutorial aimed at Rust beginners](https://github.com/rust-community/rustbridge)
- [Blog Series-multiple blog posts about Rust ML](https://tiberiusferreira.github.io/blog/)
- [Track the statre of Rust on the Machine learning field](https://www.arewelearningyet.com/)

## Programming Languages 2

**CS part:**<br>
This part should cover the materials needed to learn about designing programming languages, it's lengthy subject, my recommendation for anyone want to study it is to follow [Oregon Programming Languages Summer School](https://www.cs.uoregon.edu/research/summerschool/summer12/curriculum.html) Curriculum, in addition to some books like [Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/tapl/) and [Category Theory for Programmers](https://www.blurb.com/b/9621951-category-theory-for-programmers-new-edition-hardco).

**Rust part:**<br>

- [**Blog Series**-A series about making a programming language called Eldiro using the Rust programming language.](https://arzg.github.io/lang/) (read pratt pasing first)
- [**Playlist**-Writing a Programming Language](https://www.youtube.com/watch?v=XOOBL3bhFHs&list=PLkpGh2gaaueyzEAn07jf44LdscDeWRyzy)
- [**Book**-Create Your Own Programming Language with Rust](https://createlang.rs/)

## Extra

Courses that are not necessary but I think they are cool


| Course name                                                                                                                                                                                               | Associated Book | Other Resources | Prerequisite |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ----------------- | -------------- |
| [Introduction to Computational Thinking](https://computationalthinking.mit.edu/Fall20/)                                                                                                                   | /               | /               | /            |
| [Game Theory Part1](https://www.coursera.org/learn/game-theory-1)                                                                                                                                        | /               | /               | /            |
| [Game Theory Part2](https://www.coursera.org/learn/game-theory-2)                                                                                                                                        | /               | /               | /            |
| [Ben Eater's Build an 8-bit computer from scratch](https://eater.net/8bit)                                                                                                                                | /               | /               | /            |
| [The Art of Multiprocessor Programming](https://www.elsevier.com/books/the-art-of-multiprocessor-programming/herlihy/978-0-12-415950-1) teaching both the theory of concurrency and practical algorithms. | /               | /               | /            |
| [Great ressouces about designing systems](https://github.com/madd86/awesome-system-design)                                                                                                                | /               | /               | /            |
| [Extra list of classic books](https://www.reddit.com/r/learnprogramming/comments/dd6e0g/what_are_your_favorite_books_on_general_cs/f2f270w/?utm_source=share&utm_medium=web2x&context=3)                  | /               | /               | /            |

# What else I can do with Rust?

Choose topics that interest you and study them while going through the curriculum.

## CLI

- [Diving into Rust with a CLI](https://kbknapp.dev/rust-cli/)
- [**Book**-Command Line Book](https://rust-cli.github.io/book/index.html)
- [**Book**-Command-Line Rust](https://www.oreilly.com/library/view/command-line-rust/9781098109424/) [Repo](https://github.com/kyclark/command-line-rust) Learn the language by writing Rust versions of common Unix coreutils like head, tail, cal, cut, comm, etc.
- Crates
  - [StructOpt, parses command line arguments by defining a struct](https://crates.io/crates/structopt)
  - [Clap, Command Line Argument Parser for Rust](https://github.com/clap-rs/clap)
  - [tui-rs, library to build rich terminal user interfaces and dashboards.](https://github.com/fdehau/tui-rs)
  - [Cursive, a TUI (Text User Interface) library for rust.](https://github.com/gyscos/Cursive)
  - [Termion,manipulation terminals.](https://github.com/redox-os/termion)
  - [Crossterm, pure-rust, terminal manipulation](https://github.com/crossterm-rs/crossterm)
  - [pancurses, a curses library for Rust](https://github.com/ihalila/pancurses)

## Web

- [Rust web framework list and comparison](https://github.com/flosse/rust-web-framework-comparison)
- [**Book**-Zero to Production in Rust](https://www.zero2prod.com/index.html?country=Algeria&discount_code=AF60) [Repo](https://github.com/LukeMathWalker/zero-to-production)
- [**Book**-Black Hat Rust](https://kerkour.com/black-hat-rust)
- [**Book**-Rust Servers, Services, and Apps](https://www.manning.com/books/rust-servers-services-and-apps)
- [**Book**-Rust Web Development](https://www.manning.com/books/rust-web-development)
- [Build a Smart Bookmarking Tool with Rust and Rocket and Heruko](https://developers.facebook.com/blog/post/2020/06/03/build-smart-bookmarking-tool-rust-rocket/)

## Games

- [Learning Rust by Coding a Game of Snake](https://snake.rustbridge.com/#learning-rust-by-coding-a-game-of-snake)
- [Tic Tac Toe](https://minimax.dev/docs/ultimate/)
- [Sokoban Game](https://sokoban.iolivia.me/c01-00-intro.html)
- [**Book**-Hands-on Rust: A hands-on guide to learning Rust by making games](https://pragprog.com/titles/hwrust/hands-on-rust/)
- [**Book**-The ray tracer challenge](http://raytracerchallenge.com/)
- [Writing a Rust Roguelike for the Desktop and the Web](https://aimlesslygoingforward.com/blog/2019/02/09/writing-a-rust-roguelike-for-the-desktop-and-the-web/)
- [Roguelike Tutorial in Rust + tcod](https://tomassedovic.github.io/roguelike-tutorial/)

## Web Assembly

- [webassembly.org](https://webassembly.org/)
- [Official WebAssembly Rust page](https://www.rust-lang.org/what/wasm)
- [**Book**-WebAssembly Book](https://rustwasm.github.io/docs/book/)
- [WebAssembly Mozilla Dev network](https://developer.mozilla.org/en-US/docs/WebAssembly)
- [wasm.builders](https://www.wasm.builders/)
- [Rust-and-webassembly-from-scratch](https://depth-first.com/articles/2020/07/07/rust-and-webassembly-from-scratch-hello-world-with-strings/)
- [Using Rust and WebAssembly to Process Pixels from a Video Feed](https://dev.to/fallenstedt/using-rust-and-webassembly-to-process-pixels-from-a-video-feed-4hhg)
- [Bringing WebAssembly outside the web with WASI](https://www.youtube.com/watch?v=fh9WXPu0hw8)
- [Getting started with Rust functions in Node.js](https://www.secondstate.io/articles/getting-started-with-rust-function/)
- [**Book**-Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust)
- [Hello wasm-pack!](https://rustwasm.github.io/docs/wasm-pack/) - documentation and tutorials on how to use wasm-pack
- [The wasm-pack Guide](https://rustwasm.github.io/docs/wasm-pack/)
- [WASM it](https://azriel.im/wasm_it/)
- [The wasm-bindgen Guide](https://rustwasm.github.io/docs/wasm-bindgen/introduction.html)
- [Writing a Rust Roguelike for the Desktop and the Web](https://aimlesslygoingforward.com/blog/2019/02/09/writing-a-rust-roguelike-for-the-desktop-and-the-web/)
- [Create a simulation of evolution using neural network and genetic algorithm, and compile the application to WebAssembly](https://pwy.io/en/posts/learning-to-fly-pt1/)
- [Rust Raytracer compiled to Webassembly to run live in browser](https://www.reddit.com/r/rust/comments/s9yki0/rust_raytracer_compiled_to_webassembly_to_run/)

## Gui

- [FLTK Rust gui tutorial: Basics](https://www.youtube.com/watch?v=ygP4egJtmzw)
- [How I Built a Cross-Platform Desktop Application with Svelte, Redis, and Rust](https://css-tricks.com/how-i-built-a-cross-platform-desktop-application-with-svelte-redis-and-rust/)
- [Druid](https://linebender.org/druid/)
- [Druid todo Tutorial](https://github.com/futurepaul/druid-todo-tutorial)
- [**Book**-gtk4-rs book](https://gtk-rs.org/gtk4-rs/git/book/)
- [**Book**-GUI development with Relm4](https://aaronerhardt.github.io/relm4-book/book/)
- [7 GUI Tasks](https://eugenkiss.github.io/7guis/tasks/)

## Mobile Apps

- [Flutter+Rust](https://github.com/shekohex/flutterust)
- [Using WebAssembly in Flutter Web](https://gpalma.pt/blog/flutter-web-web-assembly/)
- [Write UI using Flutter, a cross-platform hot-reload high-performance toolkit, seamlessly with Rust](https://www.reddit.com/r/rust/comments/swrbyv/write_ui_using_flutter_a_crossplatform_hotreload/)
- [rust-on-mobile](https://github.com/mtak-/rust-on-mobile)
- [Rust on iOS](https://medium.com/visly/rust-on-ios-39f799b3c1dd)
- [Building and Deploying a Rust library on Android](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-21-rust-on-android.html)
- [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html)

## Blockchain

- [**Book**-Blockchain For Rust Developers](https://www.amazon.com/Blockchain-Rust-Developers-application-Hands/dp/B0874JFXSD/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=1592558073&sr=8-1)
- [Awesome Blockchain Rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust)
- [Rust in Blockchain](https://rustinblockchain.org/)
- [Where is the best place to learn Rust in context of Crypto/Blockchain](https://www.reddit.com/r/rust/comments/mz5m9p/where_is_the_best_place_to_learn_rust_in_context/)

# Rust Handy references

These are useful resources but are not meant to be read cover to cover. Instead, use them every time you are developing a project. you'll find references for some features that you may have a hard time understanding or help you when you are wondering what's the best way to read a file or parse an argument.

### Use While Developing your Project

- **Cheat Sheets:**

  - [Rust: How to create an awesome GitHub project!](https://www.youtube.com/watch?v=meAz2RQMHvM)
  - [Rust Cheat Sheet](https://cheats.rs/)
  - [Another Cheat sheet](https://www.breakdown-notes.com/make/load/rust_cs_canvas)
  - [Rust Types Methods Cheat sheet](https://upsuper.github.io/rust-cheatsheet/)
  - [Another Rust Types Methods Cheat sheet](http://phaiax.github.io/rust-cheatsheet/)
  - [The Periodic Table of Rust Types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/)
  - [Rust Ownership Cheat sheet](https://github.com/kmcallister/rustic-symmetries/blob/master/README.md#rustic-symmetries)
  - [Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html)
  - [Rust Container Cheat Sheet](https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/edit#slide=id.p)
  - [Learn Rust with a few minutes to spare](https://learnxinyminutes.com/docs/rust/)
  - [Do the same things in Rust!](https://programming-idioms.org/cheatsheet/Python/Rust)
  - [Notes for small Rust snippets](https://www.rustnote.com/rustnote.html)
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
  - [There are no mutable parameters in Rust](https://www.snoyman.com/blog/2020/05/no-mutable-parameters-in-rust/)
  - [Rust Module System](https://www.sheshbabu.com/posts/rust-module-system/)
  - [Mixing matching, mutation, and moves in Rust](https://blog.rust-lang.org/2015/04/17/Enums-match-mutation-and-moves.html)
  - [Rust Ownership, the Hard Way](https://chrismorgan.info/blog/rust-ownership-the-hard-way/)
  - [Tour of Rust's Standard Library Traits](https://github.com/pretzelhammer/rust-blog/blob/master/posts/tour-of-rusts-standard-library-traits.md)
  - [Understanding Rust Lifetimes](https://medium.com/nearprotocol/understanding-rust-lifetimes-e813bcd405fa)
  - [Common Rust Lifetime Misconceptions](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md)
  - [String concatenations benchmarks (updated)](https://www.reddit.com/r/rust/comments/t06hk7/string_concatenations_benchmarks_updated/)
  - **Closures:**
    - [How Rust Achieves Thread Safety](https://manishearth.github.io/blog/2015/05/30/how-rust-achieves-thread-safety/) - [Manish Goregaokar](https://github.com/Manishearth)
    - [Understanding Closures in Rust](https://medium.com/swlh/understanding-closures-in-rust-21f286ed1759)
    - [Why Rust Closures are (Somewhat) Hard](https://stevedonovan.github.io/rustifications/2018/08/18/rust-closures-are-hard.html)
  - **Iterators:**
    - [Little tour of multiple iterators implementation in Rust](https://blog.guillaume-gomez.fr/articles/2017-03-09+Little+tour+of+multiple+iterators+implementation+in+Rust)
    - [for loops in Rust](http://xion.io/post/code/rust-for-loop.html) - Karol Kuczmarski
    - [Iteration patterns for Result & Option](http://xion.io/post/code/rust-iter-patterns.html) - Karol Kuczmarski
    - [rust-iterators](https://github.com/rustomax/rust-iterators/) - Max Skybin
  - **Macros:**
    - [The Little Book of Rust Macros](https://veykril.github.io/tlborm/) This book is an attempt to distill the Rust community's collective knowledge of Rust macros.
    - [Rust macro development case studies](https://github.com/dtolnay/case-studies)
    - [Rust Latam: procedural macros workshop](https://github.com/dtolnay/proc-macro-workshop) _This repo contains a selection of projects designed to learn to write Rust procedural macros — Rust code that generates Rust code.
  - **Async, Concurrency & Parallelism:**
    - [Rust &TheMachine](https://medium.com/@orbitalK/why-the-machine-b9803a77fa29)
    - [Stakker actor runtime guide: a low-level single-thread actor runtime for Rust](https://uazu.github.io/stakker/about.html)
    - [Real-Time Interrupt-driven Concurrency](https://rtic.rs/)
    - [Hands-On Concurrency with Rust](https://www.amazon.com/Hands-Concurrency-Rust-Confidently-memory-safe/dp/1788399978)
    - [Futures Explained in 200 Lines of Rust](https://cfsamson.github.io/books-futures-explained/)
    - [areweasyncyet.rs/](https://areweasyncyet.rs/)
    - [Asynchronous Programming in Rust](https://rust-lang.github.io/async-book/01_getting_started/01_chapter.html)
    - [Async-std](https://book.async.rs/introduction.html)
    - [A practical guide to async in Rust](https://blog.logrocket.com/a-practical-guide-to-async-in-rust/)
    - [Systems with JT: Async/await in Rust](https://www.youtube.com/watch?v=FNcXf-4CLH0)
    - [The Node Experiment - Exploring Async Basics with Rust](https://cfsamson.github.io/book-exploring-async-basics/)
    - [Tokio Tutorial](https://tokio.rs/tokio/tutorial) - event-driven, non-blocking I/O
  - **FFI:**
    - [I C and .so does Rust](https://prateeknischal.github.io/posts/i-c-and-so-does-rust/)
    - [The Rust FFI Guide - using unsafe for fun and profit](https://michael-f-bryan.github.io/rust-ffi-guide/) - Michael-F-Brya
    - [Writing fast and safe native Node.js modules with Rust](https://blog.risingstack.com/node-js-native-modules-with-rust/) - Peter Czibik
    - [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/)
    - [The (unofficial) Rust FFI Guide](https://michael-f-bryan.github.io/rust-ffi-guide/) - FFI in depth
- **Guidelines and Idioms:**

  - [Rust Cook Book](https://rust-lang-nursery.github.io/rust-cookbook/) a collection of simple examples that demonstrate good practices to accomplish common programming tasks.
  - [Rust API guidelines](https://rust-lang.github.io/api-guidelines/) An extensive list of recommendations for idiomatic Rust APIs.
  - [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)  A catalogue of design patterns in Rust.
  - [Elegant Library APIs in Rust](https://scribbles.pascalhertleif.de/elegant-apis-in-rust.html)
  - [Effective Rust](https://www.lurklurk.org/effective-rust/) - Rust guidelines
  - [Rust Programming Tipz](https://github.com/ferrous-systems/elements-of-rust) A collection of software engineering techniques for effectively expressing intent with Rust.
  - [The Rust Performance Book](https://nnethercote.github.io/perf-book/title-page.html#the-rust-performance-book)
  - [Secure Rust Guidelines](https://anssi-fr.github.io/rust-guide/01_introduction.html)
  - [Wrapping errors in Rust](https://edgarluque.com/blog/wrapping-errors-in-rust) by [Edgar Luque](https://github.com/edg-l) - Wrapping `reqwest::Error` and a custom error type as an enum to make library usage easier. Also mentions [thiserror](https://github.com/dtolnay/thiserror) to automate that process.
  - [Context-preserving error handling](https://kazlauskas.me/entries/errors) by [Simonas Kazlauskas](https://github.com/nagisa) - Explains how to use crates like `thiserror` in combination with `map_err` to add context to errors to prevent information loss.
  - [stdx:  Learn these crates first as an extension to std](https://github.com/brson/stdx)
  - [Common Newbie Mistakes and Bad Practices in Rust: Bad Habits](https://adventures.michaelfbryan.com/posts/rust-best-practices/bad-habits)
  - [Tips for Faster Rust Compile Times](https://endler.dev/2020/rust-compile-times/)
  - [Compile Time Feature Flags in Rust](https://www.worthe-it.co.za/programming/2018/11/18/compile-time-feature-flags-in-rust.html)
  - [Are out parameters idiomatic in Rust?](https://steveklabnik.com/writing/are-out-parameters-idiomatic-in-rust) - Discusses the pros and cons of functions returning a value vs. modifying a parameter in-place.
  - [Aiming for idiomatic Rust](https://shane-o.dev/blog/aiming-for-idiomatic-rust)  Discusses different ways to solve a popular coding puzzle, "balanced brackets", in Rust.
  - [Possible Rust](https://www.possiblerust.com/) A blog for intermediate Rust programmers exploring real-world code and design patterns.
  - [Hexagonal architecture in Rust](https://alexis-lozano.com/hexagonal-architecture-in-rust-1/)
- **Debugging:**

  - [explaine.rs](https://jrvidal.github.io/explaine.rs/)
  - [Compiler Explorer](https://rust.godbolt.org/)
  - [Pernos](https://pernos.co/)  [demo](https://www.youtube.com/watch?v=uTc7KCBbVFI&t=162s)
  - [Debugging a segfault in my Rust program](https://jvns.ca/blog/2017/12/23/segfault-debugging/)
  - [Profiling Rust applications on Linux](http://llogiq.github.io/2015/07/15/profiling.html)
- **Tools:**

  - [Awesome Rust: Development Tools](https://github.com/rust-unofficial/awesome-rust#development-tools)
  - [Awesome Rust: Libraries](https://github.com/rust-unofficial/awesome-rust#libraries)
  - [Caniuse.rs - Rust feature search](https://caniuse.rs/)
  - [Rust external web APIs: The definitive guide](https://blog.logrocket.com/rust-external-web-apis-the-definitive-guide/) Githib api, Discord...etc

### Use to finalize your Project

- [Rust verification tools](https://alastairreid.github.io/rust-verification-tools/)
- [Rust Fuzz Book](https://rust-fuzz.github.io/book/) Fuzz testing
- [Great Rust CI](https://dev.to/cad97/great-rust-ci-1fk6)
- [Keeping Rust projects' README.md code examples up-to-date](https://blog.guillaume-gomez.fr/articles/2019-04-13+Keeping+Rust+projects%27+README.md+code+examples+up-to-date)
- [Guide on how to write documentation for a Rust crate](https://blog.guillaume-gomez.fr/articles/2020-03-12+Guide+on+how+to+write+documentation+for+a+Rust+crate) - Writing good documentation with rustdoc including many examples.
- [rust-cross, Everything you need to know about cross compiling Rust programs!](https://github.com/japaric/rust-cross) - [Jorge Aparicio](https://github.com/japaric)
- **Building an open source project?**
  - [TP 101: Introduction to open source software](https://github.com/pingcap/talent-plan/blob/master/courses/tp101-intro-to-oss.md)
  - [TP 102: How to use Git and GitHub](https://github.com/pingcap/talent-plan/blob/master/courses/tp102-how-to-use-git-github.md)
  - [TP 103: Build a welcoming community](https://github.com/pingcap/talent-plan/blob/master/courses/tp103-open-source-community.md)

# Projects, Workshops & Live Streams

- [Projects-from-Scratch](https://github.com/AlgoryL/Projects-from-Scratch) Projects Ideas.
- [Learning Parser Combinators With Rust](https://bodil.lol/parser-combinators/)
- [**Blog**-Rust and CSV Parsing](http://blog.burntsushi.net/csv/)
- [Learning Rust: Let's Build a Parser!](https://codeandbitters.com/lets-build-a-parser/)
- [Why your first FizzBuzz implementation may not work](http://chrismorgan.info/blog/rust-fizzbuzz.html)
- [Web browser from scratch in Rust](https://joshondesign.com/tags/browser)
- [Implementing ArrayVec Using Const Generics](https://adventures.michaelfbryan.com/posts/const-arrayvec/)
- Codebases:
  - [ripgrep (rg)](https://github.com/BurntSushi/ripgrep) a line-oriented search tool.
  - [Tealdeer (tldr)](https://github.com/dbrgn/tealdeer) a fast cli tool to learn basic uses for many commands
  - [GNU coreutils in Rust](https://github.com/uutils/coreutils)
  - [Awesome Rust: Applications](https://github.com/rust-unofficial/awesome-rust#applications)
- Rewrite in Rust
  - [A Regular Expression Matcher](https://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html)
  - [Regular Expression Matching Can Be Simple And Fast](https://swtch.com/~rsc/regexp/regexp1.html)
  - [Projects Ideas](https://www.reddit.com/r/learnrust/comments/k3od5w/comment/ge6z7rx/?utm_source=share&utm_medium=web2x&context=3)

# Blogs and Channels

- [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming)
- [Hackr.io: most upvoted Rust ressources](https://hackr.io/tutorials/learn-rust?sort=upvotes)
- [Morioh](https://morioh.com/topic/rust)
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
- [Antoyo's Blog](https://blog.antoyo.xyz/)
- [Sylvain Kerkour](https://kerkour.com/)
- [matklad](https://matklad.github.io/)
- [Manning Publications Rust channel](https://www.youtube.com/c/ManningPublications/search?query=rust)
- [Gamozolabs](https://www.youtube.com/c/gamozolabs/playlists) Security researcher who writes everything in rust, primarily focused on fuzzing

# Rust Community

- [The Rust Programming Language Forum](https://users.rust-lang.org/)
- [Stackoverflow Rust questions](https://stackoverflow.com/questions/tagged/rust)
- [Rust Mentors](https://rustbeginners.github.io/awesome-rust-mentors/)
- [Rustacean Station](https://rustacean-station.org/)
- [Rust-Saar](https://rust.saarland/)
- [Rust Programming Language Community Discord Server](https://discord.gg/rust-lang-community)
- [Rust Programming Language Official Discord Server](https://discord.gg/98ApvsFeCq)
- [Rustacean Station Discord Server](https://discord.gg/ZFbGFF9T3J)
- [Rust بالعربي Discord Server](https://discord.gg/UFFcsKsDx4)
- [zulip chat](https://rust-lang.zulipchat.com/)

# Crates and Libs

- [Fuzz testing](https://github.com/rust-fuzz/afl.rs)
- [the pest parser](https://pest.rs/book/) a library for writing plain-text parsers in Rust.
- [awesomo /rust](https://github.com/lk-geimfari/awesomo/blob/master/languages/RUST.md)
- [Serde JSON](https://github.com/serde-rs/json)
- [Dyner](https://dyner.netlify.app/) experimental trait (_dyn_) objects in Rust

# Jobs

- [RustJobs](https://rustjobs.dev/)
- [Companies that use Rust](https://www.rust-lang.org/production/users)

# Sources

These are some of the sources I used for the Rust parts of this curriculum.

- [Rust Books](https://github.com/sger/RustBooks) (commit of Mar 17, 2022 )
- [Awesome Rust, A curated list of Rust code and resources.](https://github.com/rust-unofficial/awesome-rust) (commit of Mar 22, 2022 )
- [Idiomatic Rust](https://github.com/mre/idiomatic-rust) (commit of Mar 7, 2022)
- [The Little Book of Rust Books](https://lborb.github.io/book/title-page.html) (commit of Mar 10, 2022 )
- [Project Based Learning](https://github.com/practical-tutorials/project-based-learning#rust) (commit of Jan 28, 2022)
- [Build your Own X](https://github.com/danistefanovic/build-your-own-x) (commit of Feb 16, 2022)
- [Rust-learning, A list of Ressources](https://github.com/ctjhoa/rust-learning) (commit of Mar 25, 2022)
- [a collection of substantial blog posts about Rust](https://github.com/brson/rust-anthology/blob/master/master-list.md)
