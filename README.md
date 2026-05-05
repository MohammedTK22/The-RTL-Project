# The RTL Project
The Ready-To-Learn (RTL) Project was started because the author stumbled across many amazing resources that he'd wish he encountered sooner. Everything you find here is 
a curated collection of free, public resources to help Imperial EEE/EIE build practical technical skills and excel in internship, placement, and graduate job interviews.
> **Note:** Many links were initially gathered using AI tools; the repo is continuously refined to remove redundancies and improve quality.
 
---
 
## 📑 Table of Contents
 
- [Linux, Bash & the Command Line](#linux-bash--the-command-line)
- [Version Control with Git & GitHub](#version-control-with-git--github)
- [Programming Languages](#programming-languages)
- [Data Structures, Algorithms & Interview Prep](#data-structures-algorithms--interview-prep)
- [Analog, Power Electronics & Semiconductors](#analog-power-electronics--semiconductors)
- [Computer Architecture, OS, Compilers & Networks](#computer-architecture-os-compilers--networks)
- [Robotics & Control Engineering](#robotics--control-engineering)
- [Electromagnetism & RF Design](#electromagnetism--rf-design)
- [Hardware, FPGA, Systems & Quantum](#hardware-fpga-systems--quantum)
- [Advanced Signal & Image Processing](#advanced-signal--image-processing)
- [Embedded Systems & Microcontrollers](#embedded-systems--microcontrollers)
- [AI, Machine Learning & CUDA GPU Programming](#ai-machine-learning--cuda-gpu-programming)
- [DevOps, Containers & CI/CD](#devops-containers--cicd)
- [Computer Science & Mathematics](#computer-science--mathematics)
- [Practical Engineering Tools & Free Software](#practical-engineering-tools--free-software)
- [Build It: Project Setup & Inspiration](#-build-it-project-setup--inspiration)
- [Career, CV & Interview Preparation](#-career-cv--interview-preparation)
---
 
## Linux, Bash & the Command Line
 
If you take away one thing from this repo, let it be this: **learn Linux**. Almost every embedded system, server, cloud platform, and HPC cluster you will ever touch runs Linux. Employers expect you to be comfortable at a terminal.
 
*   [The Missing Semester of Your CS Education (MIT)](https://missing.csail.mit.edu/) - Covers everything your degree doesn't: the shell, Vim, Git, debugging, profiling, security, and more. Arguably the single most valuable free course for any engineering student. Has accompanying YouTube lectures.
*   [Linux Journey](https://linuxjourney.com/) - A beautiful, beginner-friendly walkthrough of Linux fundamentals: the command line, filesystem, permissions, processes, packages, networking, and the kernel.
*   [Ryan's Linux Tutorial](https://ryanstutorials.net/linuxtutorial/) - Concise, practical guide covering the Linux command line, file manipulation, permissions, piping, and grep/awk/sed.
*   [The Linux Command Line (Book by William Shotts)](https://linuxcommand.org/tlcl.php) - The full PDF is free. An incredibly well-written 500-page book that takes you from absolute beginner to shell scripting competency.
*   [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) - Learn Linux commands through a gamified, SSH-based wargame. Great fun and incredibly educational.
*   [Linux From Scratch](https://www.linuxfromscratch.org/) - Build an entire Linux system from source code. Deep understanding guaranteed.
*   [Bash Scripting Tutorial (Ryan's Tutorials)](https://ryanstutorials.net/bash-scripting-tutorial/) - Clear 8-part tutorial covering variables, input, if statements, loops, and functions.
*   [freeCodeCamp: Bash Scripting Tutorial](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/) - Comprehensive written guide with inline examples.
*   [Introduction to Bash Scripting (GitHub eBook)](https://github.com/bobbyiliev/introduction-to-bash-scripting) - Open-source ebook with 13 foundational chapters plus real-world script examples.
*   [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/) - The official, authoritative reference. Bookmark it.
*   [ShellCheck](https://www.shellcheck.net/) - Paste your shell scripts in and get instant linting and best-practice feedback. Also available as a CLI/CI tool.
*   [Explain Shell](https://explainshell.com/) - Paste any shell command and get a visual breakdown of every flag and argument.
*   [W3Schools Bash Tutorial](https://www.w3schools.com/bash/) - Interactive browser-based Bash tutorial covering scripting, loops, conditionals, and system commands.
*   [Linuxize](https://linuxize.com/) - Hundreds of high-quality, practical "how-to" articles for Linux commands and system administration.
---
 
## Version Control with Git & GitHub
 
Every technical role — hardware, software, firmware, DevOps — requires Git. Learn it early, use it for every project, and put your work on GitHub. Recruiters **will** look at your profile.
 
*   [Pro Git (Book)](https://git-scm.com/book/en/v2) - The definitive free book on Git. Read at least Chapters 1–3 and 6 (branching strategies).
*   [Git Immersion](https://gitimmersion.com/) - A guided, hands-on tour through Git fundamentals using a series of small labs.
*   [Learn Git Branching](https://learngitbranching.js.org/) - An interactive, visual tool that lets you experiment with Git branching, merging, rebasing, and cherry-picking in your browser. Extremely good.
*   [GitHub Skills](https://skills.github.com/) - Official GitHub interactive courses covering repos, branches, pull requests, GitHub Pages, GitHub Actions, and more.
*   [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials) - Well-written guides with diagrams covering everything from basics to advanced workflows (Gitflow, forking workflow, etc.).
*   [Oh My Git!](https://ohmygit.org/) - An open-source game to learn Git concepts visually.
*   [Conventional Commits](https://www.conventionalcommits.org/) - Learn the industry-standard commit message format used across open-source and enterprise projects.
*   [GitHub Student Developer Pack](https://education.github.com/pack) - Free access to dozens of developer tools (domains, cloud credits, CI/CD minutes, etc.) with your university email.
---
 
## Programming Languages
 
### C
*   [Beej's Guide to C Programming](https://beej.us/guide/bgc/) - Excellent, highly readable guide to standard C. Essential for embedded and systems programming.
*   [C Programming: A Modern Approach (K.N. King)](http://knking.com/books/c2/) - Widely considered the best C textbook. The companion site has exercises and errata.
*   [CS50 Manual Pages](https://manual.cs50.io/) - Harvard's simplified man pages for standard C library functions. Very helpful when learning.
*   [Build Your Own Lisp](https://buildyourownlisp.com/) - Learn C by building a real programming language from scratch.
### C++
*   [LearnCpp.com](https://www.learncpp.com/) - The best free tutorial for learning modern C++ (C++11 through C++23) from the ground up. Extremely thorough.
*   [Hacking C++ (Cheat Sheets & Guides)](https://hackingcpp.com/) - Beautiful visual reference cards for C++ STL containers, algorithms, iterators, and memory management.
*   [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines) - Maintained by Bjarne Stroustrup and Herb Sutter. Learn how to write modern, safe, idiomatic C++.
*   [Compiler Explorer (Godbolt)](https://godbolt.org/) - See exactly what assembly your C/C++ code compiles to. Incredibly useful for understanding performance and compiler behavior.
### Python
*   [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) - Great practical introduction. Available free as HTML.
*   [Python for Everybody (Dr. Chuck)](https://www.py4e.com/) - Gentle introduction with accompanying Coursera course and free textbook.
*   [Real Python](https://realpython.com/) - Hundreds of high-quality tutorials covering everything from basics to advanced topics (async, decorators, packaging). Some content is paywalled but most tutorials are free.
*   [Scientific Python Lectures (GitHub)](https://github.com/jrjohansson/scientific-python-lectures) - Jupyter notebooks covering NumPy, SciPy, Matplotlib, and SymPy. Perfect for EEE/physics students.
*   [Python Tutor](https://pythontutor.com/) - Visualise Python (and C/C++/Java/JS) code execution step-by-step. Invaluable for debugging and understanding memory.
*   [Full Stack Python](https://www.fullstackpython.com/) - Everything you need to deploy real Python web applications: frameworks, databases, servers, and DevOps.
### Rust
*   [The Rust Programming Language ("The Book")](https://doc.rust-lang.org/book/) - The official, free, comprehensive guide. Start here.
*   [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - Learn Rust through annotated, runnable code examples.
*   [Rustlings](https://github.com/rust-lang/rustlings) - Small exercises to get you used to reading and writing Rust code, including fixing compiler errors.
*   [The Embedded Rust Book](https://docs.rust-embedded.org/book/) - Learn embedded systems programming (bare-metal ARM) using Rust. Directly relevant for EEE/EIE students.
*   [Comprehensive Rust (Google)](https://google.github.io/comprehensive-rust/) - Google's 4-day Rust course, freely available, covering everything from basics to async and bare-metal.
### Go
*   [A Tour of Go](https://go.dev/tour/) - The official interactive tutorial. Complete it in an afternoon.
*   [Go by Example](https://gobyexample.com/) - Annotated example programs covering the entire language.
*   [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests/) - Test-Driven Development approach to learning Go. Teaches you testing discipline and Go simultaneously.
*   [Effective Go](https://go.dev/doc/effective_go) - The official guide to writing clear, idiomatic Go code.
### Java
*   [MOOC.fi Java Programming (University of Helsinki)](https://java-programming.mooc.fi/) - Excellent, free, project-based course with automated grading. Two parts, each equivalent to a university module.
*   [Baeldung](https://www.baeldung.com/) - The go-to reference site for Java and Spring tutorials.
### JavaScript / TypeScript
*   [javascript.info (The Modern JavaScript Tutorial)](https://javascript.info/) - The most comprehensive, up-to-date free JS resource available. Covers language fundamentals, DOM, async, and more.
*   [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/) - The official guide. Essential reading if you're building web applications or tooling.
*   [Eloquent JavaScript](https://eloquentjavascript.net/) - Free online book covering JS from basics to Node.js, with interactive code examples in every chapter.
*   [The Odin Project](https://www.theodinproject.com/) - A full, free curriculum for learning full-stack web development (HTML/CSS/JS/React/Node). Heavily project-based.
*   [freeCodeCamp](https://www.freecodecamp.org/learn) - 3,000+ hours of free, interactive coding curriculum with certifications. Covers HTML, CSS, JS, Python, data science, and more.
### Assembly & Low-Level
*   [RISC-V Assembly Programming (Book)](https://riscv-programming.org/book.html) - Free book for learning RISC-V assembly, directly relevant to the Imperial EIE curriculum.
*   [x86 Assembly Guide (University of Virginia)](https://www.cs.virginia.edu/~evans/cs216/guides/x86.html) - Clean, concise reference for x86 assembly programming.
*   [NASM Tutorial](https://cs.lmu.edu/~ray/notes/nasmtutorial/) - Practical guide for writing x86-64 assembly on Linux.
### MATLAB / Octave
*   [GNU Octave](https://octave.org/) - Free, open-source MATLAB alternative. Runs most MATLAB syntax.
*   [MATLAB Onramp (MathWorks)](https://matlabacademy.mathworks.com/) - Free 2-hour official interactive tutorial. Imperial students get MATLAB for free through the university.
*   [Control Tutorials for MATLAB and Simulink (CTMS)](https://ctms.engin.umich.edu/CTMS/index.php) - UMich/CMU joint project walking you through controller design for physical systems.
### Verilog / SystemVerilog
*   [HDLBits](https://hdlbits.01xz.net/) - LeetCode for Verilog. Interactive web-based testbenches to practise writing HDL.
*   [ASIC World Verilog Tutorial](https://www.asic-world.com/verilog/veritut.html) - Comprehensive reference for Verilog syntax and design patterns.
*   [SystemVerilog for Verification (ChipVerify)](https://www.chipverify.com/systemverilog/systemverilog-tutorial) - Tutorials on SV constructs used in modern hardware verification.
### Other Useful Languages
*   [Learn Shell (Interactive)](https://www.learnshell.org/) - Browser-based interactive tutorial for shell/Bash scripting.
*   [SQL Tutorial (Mode Analytics)](https://mode.com/sql-tutorial) - Learn SQL through interactive exercises. Valuable for data engineering and analytics roles.
*   [SQLBolt](https://sqlbolt.com/) - Interactive, bite-sized SQL lessons with inline exercises.
*   [Exercism](https://exercism.org/) - Free, mentor-guided coding practice across 70+ languages.
*   [Codecademy: Learn Bash Scripting (Free)](https://www.codecademy.com/learn/bash-scripting) - Interactive browser-based Bash course.
*   [LaTeX Tutorial (Overleaf)](https://www.overleaf.com/learn) - Learn LaTeX for writing reports, papers, and your FYP. Imperial uses Overleaf heavily.
---
 
## Data Structures, Algorithms & Interview Prep
 
If you want a software engineering internship at a top company, you need to grind DSA. There's no shortcut, but these resources make it structured and efficient.
 
*   [LeetCode](https://leetcode.com/) - The industry standard for software engineering technical interviews.
*   [NeetCode](https://neetcode.io/) - Curated LeetCode roadmap with video explanations. Start with the "NeetCode 150" list.
*   [Blind 75](https://www.techinterviewhandbook.org/grind75) - The original curated list of 75 must-know problems (now "Grind 75" with a configurable schedule).
*   [HackerRank](https://www.hackerrank.com/) - Frequently used for company online assessments (OAs). Practise here.
*   [Project Euler](https://projecteuler.net/) - Maths-heavy programming challenges. Good for sharpening mathematical thinking.
*   [Advent of Code](https://adventofcode.com/) - 25 days of festive programming puzzles every December. Excellent for practising in any language.
*   [Codeforces](https://codeforces.com/) - Competitive programming platform with regular rated contests. Great for building speed and problem-solving.
*   [Tech Interview Handbook](https://www.techinterviewhandbook.org/) - Comprehensive, free guide covering resume writing, behavioural questions, DSA study plans, and system design.
*   [Visualgo](https://visualgo.net/) - Animated visualisations of data structures and algorithms. Extremely helpful for building intuition.
*   [Algorithm Visualizer](https://algorithm-visualizer.org/) - Interactive platform for visualising algorithms from code.
*   [Open Data Structures](https://opendatastructures.org/) - Free textbook covering array-based lists, linked lists, hash tables, trees, and graphs with implementations in C++, Java, and Python.
*   [Introduction to Algorithms (MIT OCW 6.006)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) - Erik Demaine's legendary lectures on algorithms. The gold standard.
*   [Algorithms (Jeff Erickson)](https://jeffe.cs.illinois.edu/teaching/algorithms/) - A free, comprehensive algorithms textbook used at UIUC.
*   [Design Patterns for Humans (GitHub)](https://github.com/kamranahmedse/design-patterns-for-humans) - Plain-English explanations of all 23 Gang of Four design patterns with real-world examples.
---
 
## Analog, Power Electronics & Semiconductors
 
*   [All About Circuits Textbook](https://www.allaboutcircuits.com/textbook/) - Massive, free online textbook covering DC analysis through to semiconductors.
*   [Prof. Behzad Razavi's Electronics Lectures (YouTube)](https://www.youtube.com/watch?v=Fj2n3a0QvUU&list=PL7qKWvgGQlx_9yGksQZ5A8RjE6j1W_P_w) - UCLA's legendary professor teaching microelectronics. A must-watch for IC design.
*   [MIT OCW 6.002: Circuits and Electronics](https://ocw.mit.edu/courses/6-002-circuits-and-electronics-spring-2007/) - The gold standard introductory circuits course from MIT.
*   [Modern Semiconductor Devices for Integrated Circuits](https://www.chu.berkeley.edu/modern-semiconductor-devices-for-integrated-circuits/) - Prof. Chenming Hu's free textbook (UC Berkeley). The bible for MOSFET and FinFET physics.
*   [Sam Ben-Yaakov (YouTube)](https://www.youtube.com/user/sambenyaakov) - Deep dives into power electronics, SMPS, and SPICE simulation.
*   [MIT OCW 6.012: Microelectronic Devices and Circuits](https://ocw.mit.edu/courses/6-012-microelectronic-devices-and-circuits-fall-2009/) - Covers device physics, MOSFET models, and analog circuit design.
*   [Prof. Ali Hajimiri's Electronics Lectures (Caltech, YouTube)](https://www.youtube.com/playlist?list=PLc7Gz02Znph_HU1I9STgC4Nv0aG_jdb8Z) - Another world-class analog electronics lecturer. Covers noise, feedback, and oscillators.
*   [CircuitLab](https://www.circuitlab.com/) - Browser-based circuit simulator for quick prototyping and learning.
*   [Electronics Tutorials](https://www.electronics-tutorials.ws/) - Comprehensive written tutorials on components, circuit theory, op-amps, and filters.
*   [EEVblog (YouTube)](https://www.youtube.com/@EEVblog) - Dave Jones's massive library of teardowns, tutorials, and electronics fundamentals videos.
---
 
## Computer Architecture, OS, Compilers & Networks
 
*   [Operating Systems: Three Easy Pieces (OSTEP)](https://pages.cs.wisc.edu/~remzi/OSTEP/) - The best free textbook on OS concepts: virtualisation, memory, concurrency, and persistence.
*   [Onur Mutlu Lectures (YouTube)](https://www.youtube.com/c/OnurMutluLectures) - World-class lectures from ETH Zurich on computer architecture, memory systems, and hardware security.
*   [CS61C: Great Ideas in Computer Architecture (UC Berkeley)](https://cs61c.org/) - C, RISC-V assembly, datapath/pipelining, memory hierarchies, and parallelism.
*   [Crafting Interpreters](https://craftinginterpreters.com/) - Build a compiler and interpreter from scratch. Brilliant and free.
*   [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/) - The definitive, incredibly readable guide to sockets, TCP/IP, and network systems in C.
*   [Computer Networking: A Top-Down Approach (Companion Site)](https://gaia.cs.umass.edu/kurose_ross/wireshark.php) - Wireshark labs from the Kurose & Ross textbook. Great for hands-on networking understanding.
*   [Ben Eater (YouTube)](https://www.youtube.com/c/BenEater) - Build an 8-bit computer from scratch on breadboards. The best hardware-level computer architecture content on the internet.
*   [Computer Systems: A Programmer's Perspective (CS:APP)](https://csapp.cs.cmu.edu/) - CMU's legendary systems textbook. Labs are freely available and are extremely valuable.
*   [xv6: A Simple Unix-Like Teaching OS (MIT)](https://pdos.csail.mit.edu/6.828/2023/xv6.html) - Read and modify a real operating system kernel. The companion to MIT's 6.1810.
*   [CPU Land (Putting the You in CPU)](https://cpu.land/) - A beautifully illustrated guide to how programs actually run on CPUs, covering syscalls, virtual memory, and more.
*   [High Performance Browser Networking (Book)](https://hpbn.co/) - Free online book by Ilya Grigorik covering TCP, UDP, TLS, HTTP/2, WebSocket, and WebRTC.
---
 
## Robotics & Control Engineering
 
*   [Modern Robotics (Northwestern University)](https://modernrobotics.northwestern.edu/) - Prof. Kevin Lynch's free textbook and YouTube series covering kinematics, dynamics, and control.
*   [Brian Douglas: Control Systems Lectures (YouTube)](https://www.youtube.com/user/ControlLectures) - The best resource for intuitively understanding Bode plots, root locus, PID, and state-space.
*   [Control Tutorials for MATLAB and Simulink (CTMS)](https://ctms.engin.umich.edu/CTMS/index.php) - UMich/CMU joint project for designing controllers for physical systems.
*   [Steve Brunton: Control Bootcamp (YouTube)](https://www.youtube.com/watch?v=Pi7l8mMjYVE&list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m) - Modern state-space control, LQR, and Kalman filters.
*   [Underactuated Robotics (MIT, Russ Tedrake)](https://underactuated.csail.mit.edu/) - Free online textbook and course on advanced control for robotics: trajectory optimization, model predictive control, and reinforcement learning for physical systems.
*   [ROS 2 Documentation](https://docs.ros.org/) - Robot Operating System 2 tutorials. ROS is the industry standard middleware for robotics. Learn it.
*   [Introduction to Autonomous Robots (Free Textbook)](https://github.com/Introduction-to-Autonomous-Robots/Introduction-to-Autonomous-Robots) - Covers locomotion, manipulation, path planning, and SLAM.
*   [MATLAB Tech Talks: Control Systems (YouTube)](https://www.youtube.com/playlist?list=PLn8PRpmsu08pFBqgd_6DQ56gMRe__vLNS) - Concise, visual explanations of control concepts from MathWorks engineers.
---
 
## Electromagnetism & RF Design
 
*   [The Feynman Lectures on Physics: Volume II](https://www.feynmanlectures.caltech.edu/II_toc.html) - Caltech's free HTML version. Heavily focused on mathematical foundations of EM.
*   [MIT OCW 8.02: Electricity and Magnetism](https://ocw.mit.edu/courses/8-02-physics-ii-electricity-and-magnetism-spring-2007/) - Walter Lewin's classic, highly visual lectures on Maxwell's equations.
*   [Microwave and RF Design (Open Access Books)](https://repository.lib.ncsu.edu/handle/1840.20/36776) - 5-volume free textbook series by Prof. Michael Steer (NC State) covering RF networks, antennas, and amplifiers.
*   [Prof. Nathan Ida: Engineering Electromagnetics (Companion)](https://link.springer.com/book/10.1007/978-3-319-07806-9) - Springer open-access textbook on engineering EM.
*   [RF Cafe](https://www.rfcafe.com/) - Encyclopedia of RF engineering calculators, formulas, charts, and encyclopedic reference material.
*   [Microwaves101](https://www.microwaves101.com/) - Practical encyclopaedia of microwave engineering with industry-oriented explanations.
---
 
## Hardware, FPGA, Systems & Quantum
 
*   [FPGA Concepts](https://fpgadesign.io/fpga-concepts/) & [Digital Logic](https://fpgadesign.io/digital-logic/) - Excellent breakdowns of core hardware concepts.
*   [SystemVerilog Interview Questions](https://fpgadesign.io/sv-interview-questions/) & [Design Questions](https://fpgadesign.io/design-questions/)
*   [Cocotb Documentation](https://docs.cocotb.org/en/stable/) - Write VHDL/SystemVerilog testbenches in Python. Industry standard for modern verification.
*   [Universal Verification Methodology (GitHub)](https://github.com/universal-verification-methodology)
*   [Tiny Tapeout (Chip Design)](https://tinytapeout.com/) & [Workshop Guide](https://tinytapeout.com/guides/workshop/) - Real silicon chip design for beginners.
*   [Linux From Scratch](https://www.linuxfromscratch.org/) & [First Kernel Patch Tutorial](https://kernelnewbies.org/FirstKernelPatch)
*   [Quantum Country](https://quantum.country/) & [Riverlane Delta Kit (Quantum)](https://deltakit.riverlane.com/)
*   [Formal Methods Organization](https://formal.org/)
*   [ZipCPU Blog](https://zipcpu.com/) - Detailed, practical articles on FPGA design, formal verification, and building CPU cores.
*   [Project F: FPGA Graphics Tutorials](https://projectf.io/) - Learn graphics programming on FPGAs from first principles. Beautiful, well-documented projects.
*   [Lattice iCE40 Open-Source Toolchain (Project IceStorm)](https://clifford.at/icestorm/) - Fully open-source FPGA toolchain. Great for learning without vendor lock-in.
*   [Verilog Tutorial (ChipVerify)](https://www.chipverify.com/verilog/verilog-tutorial) - Comprehensive Verilog language reference with examples.
*   [VLSI System Design (VSD)](https://www.vlsisystemdesign.com/) - Free workshops and labs on ASIC design flow using open-source EDA tools.
---
 
## Advanced Signal & Image Processing
 
*   [Julius O. Smith III: DSP Books (Stanford CCRMA)](https://ccrma.stanford.edu/~jos/) - Free HTML textbooks covering filters, DFT mathematics, and audio applications.
*   [The Scientist and Engineer's Guide to DSP (Book)](https://www.dspguide.com/pdfbook.htm) - A highly readable foundational DSP text.
*   [DSP Guru](https://dspguru.com/) - Repository of DSP FAQs, algorithms, and practical tricks.
*   [First Principles of Computer Vision (Columbia University)](https://fpcv.cs.columbia.edu/) - Prof. Shree Nayar's free video series covering the physics of imaging and image processing.
*   [3Blue1Brown: Fourier Transform (YouTube)](https://www.youtube.com/watch?v=spUNpyF58BY) - The single best visual explanation of the Fourier Transform you will ever watch.
*   [Allen Downey: Think DSP (Book)](https://greenteapress.com/thinkdsp/html/) - Free Python-based DSP textbook. Hands-on, code-first approach.
*   [SigPy (GitHub)](https://github.com/mikgroup/sigpy) - Python package for signal processing with GPU support. Useful for MRI/medical imaging research.
*   [PySDR: A Guide to SDR and DSP using Python](https://pysdr.org/) - Learn software-defined radio and DSP from scratch using Python and real RF signals.
---
 
## Embedded Systems & Microcontrollers
 
*   [Cornell ECE 4760: Designing with Microcontrollers](https://people.ece.cornell.edu/land/courses/ece4760/) - Prof. Bruce Land's legendary resource for bare-metal C, RTOS, and hardware interfacing (Pi Pico/RP2040).
*   [Modern Embedded Systems Programming (YouTube)](https://www.youtube.com/playlist?list=PLPW8O6W-1chwyTzI3BHwBLbGQoPFxPAPM) - Miro Samek's ground-up course on how embedded processors work, down to registers and memory maps.
*   [Embedded Artistry](https://embeddedartistry.com/) - High-quality articles on embedded C best practices, RTOS design patterns, and build systems.
*   [Interrupt Blog (Memfault)](https://interrupt.memfault.com/) - Technical deep-dives on embedded firmware topics: debugging, OTA updates, RTOS, testing, and best practices.
*   [FreeRTOS Documentation](https://www.freertos.org/Documentation/RTOS_book.html) - Free book and API reference for the most widely used embedded RTOS.
*   [Raspberry Pi Documentation](https://www.raspberrypi.com/documentation/) - The starting point for IoT, robotics, and embedded Linux projects.
*   [Raspberry Pi Pico SDK Documentation](https://www.raspberrypi.com/documentation/microcontrollers/) - Official SDK docs for the RP2040/RP2350. Learn embedded C on modern ARM Cortex-M hardware.
*   [STM32 Getting Started (ST Wiki)](https://wiki.st.com/stm32mpu/wiki/Getting_started) - Official guides for STM32 development. Industry-standard ARM Cortex-M microcontrollers.
*   [Zephyr Project RTOS](https://docs.zephyrproject.org/) - Modern, vendor-neutral RTOS backed by the Linux Foundation. Growing fast in industry.
---
 
## AI, Machine Learning & CUDA GPU Programming
 
*   [Dive into Deep Learning (Book)](https://d2l.ai/chapter_preface/index.html) - Interactive DL textbook with PyTorch, TensorFlow, and JAX code.
*   [Mathematics for Machine Learning (Book)](https://mml-book.github.io/) - Free textbook covering the linear algebra, probability, and optimisation foundations.
*   [Deep Learning Systems Course](https://dlsyscourse.org/) - Build a deep learning framework from scratch.
*   [MIT 6.5940: TinyML and Efficient Deep Learning (Fall 2024)](https://hanlab.mit.edu/courses/2024-fall-65940) - Cutting-edge course on model compression, pruning, quantisation, and deployment on edge devices.
*   [Andrej Karpathy: Neural Networks: Zero to Hero (YouTube)](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) - Build neural networks from scratch in Python. Backprop, GPT, and tokenisation explained beautifully.
*   [fast.ai: Practical Deep Learning for Coders](https://course.fast.ai/) - Top-down, code-first approach to deep learning. Free course and textbook.
*   [Stanford CS231n: CNNs for Visual Recognition](https://cs231n.stanford.edu/) - Lecture notes, assignments, and slides freely available.
*   [Stanford CS224n: NLP with Deep Learning](https://web.stanford.edu/class/cs224n/) - Free lectures and assignments on transformers, attention, and language models.
*   [Sasha Rush's GPU Puzzles](https://github.com/srush/GPU-Puzzles) & [Triton Puzzles](https://github.com/srush/Triton-Puzzles) - Hands-on GPU programming exercises.
*   [Simon Boehm's CUDA Matmul Blog](https://siboehm.com/articles/22/CUDA-MMM) - Step-by-step CUDA kernel optimisation walkthrough.
*   [FlashAttention Paper](https://arxiv.org/abs/2205.05198) - The paper that changed transformer inference. Read it.
*   [GPU MODE Discord Community](https://discord.gg/gpumode) - Active community for GPU programming and ML systems.
*   [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/) - Free, comprehensive course on transformers, tokenisers, fine-tuning, and deploying NLP models.
*   [LLM101n (Andrej Karpathy, GitHub)](https://github.com/karpathy/LLM101n) - Build a Storyteller AI from scratch. Hands-on LLM education.
---
 
## DevOps, Containers & CI/CD
 
Modern engineering roles increasingly expect familiarity with containers, CI/CD pipelines, and cloud basics. Even hardware engineers benefit from automating their build/test workflows.
 
*   [Docker Getting Started Tutorial](https://docs.docker.com/get-started/) - The official Docker tutorial. Learn containers, images, volumes, and Docker Compose.
*   [Docker Curriculum (Prakhar Srivastav)](https://docker-curriculum.com/) - A comprehensive, beginner-friendly Docker tutorial that builds up to deploying on AWS.
*   [Complete Docker Course (GitHub)](https://github.com/sidpalas/devops-directive-docker-course) - Companion repo to the DevOps Directive's free YouTube course. Covers containers from theory to production.
*   [Kubernetes Basics (Official Tutorial)](https://kubernetes.io/docs/tutorials/kubernetes-basics/) - Interactive, browser-based introduction to Kubernetes concepts and kubectl.
*   [GitHub Actions Documentation](https://docs.github.com/en/actions) - Learn to automate builds, tests, and deployments directly in your GitHub repos. CI/CD is a must-know.
*   [GitLab CI/CD Tutorial](https://docs.gitlab.com/ee/ci/quick_start/) - Alternative CI/CD platform, widely used in industry.
*   [The Twelve-Factor App](https://12factor.net/) - Methodology for building modern, scalable, deployable software-as-a-service applications.
*   [DevOps Roadmap (roadmap.sh)](https://roadmap.sh/devops) - Visual, interactive roadmap of every DevOps skill you should learn and in what order.
---
 
## Computer Science & Mathematics
 
*   [CS50 on edX](https://www.edx.org/cs50) - Harvard's famous introduction to computer science.
*   [Stanford Engineering Everywhere](https://see.stanford.edu/) - Free access to Stanford's foundational engineering and CS courses.
*   [Data Science For Beginners (Microsoft GitHub)](https://github.com/microsoft/Data-Science-For-Beginners) - 10-week curriculum with 20 lessons on data science fundamentals.
*   [MIT OCW 18.06: Linear Algebra (Gilbert Strang)](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/) - The legendary linear algebra course. Essential for ML, control systems, signal processing, and graphics.
*   [3Blue1Brown: Essence of Linear Algebra (YouTube)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - The most beautiful introduction to linear algebra ever made.
*   [3Blue1Brown: Essence of Calculus (YouTube)](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) - Visual, intuitive calculus from first principles.
*   [Probability and Statistics (Seeing Theory, Brown University)](https://seeing-theory.brown.edu/) - Interactive visualisations of probability concepts.
*   [Discrete Mathematics: An Open Introduction](https://discrete.openmathbooks.org/) - Free textbook covering logic, proofs, graph theory, and combinatorics.
*   [Category Theory for Programmers (Book)](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/) - Free online book for the mathematically curious.
*   [Isabelle Theorem Prover Documentation](https://isabelle.in.tum.de/documentation.html) & [Dafny Tutorial (Termination)](https://dafny.org/latest/OnlineTutorial/Termination) - Formal verification tools.
*   [Mathematics for Computer Science (MIT OCW 6.042)](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/) - Proofs, number theory, probability, and graph theory tailored for CS students.
*   [How to Prove It (Velleman) Companion](https://users.metu.edu.tr/serMDef/courses/111-2011/textbook-math111.pdf) - Essential if you want to learn mathematical proof techniques properly.
---
 
## Practical Engineering Tools & Free Software
 
*   [Analog Devices: LTspice Simulator](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) - Industry-standard (and free) SPICE simulator for analog circuits.
*   [GNU Octave](https://octave.org/) - Free, open-source MATLAB alternative.
*   [Icarus Verilog](http://iverilog.icarus.com/) & [GTKWave](https://gtkwave.sourceforge.net/) - Free toolchain for compiling Verilog and viewing waveforms.
*   [Phil's Lab (YouTube)](https://www.youtube.com/c/PhilS94) - The best channel for PCB design, mixed-signal hardware, and STM32 firmware using KiCad.
*   [Fesz Electronics (YouTube)](https://www.youtube.com/c/FeszElectronics) - LTspice simulation deep-dives, switching power supplies, and analog design.
*   [Learn Fusion 360 in 30 Days](https://www.youtube.com/playlist?list=PLrZ2zKOtC_-DR2ZkMaK3YthYLErPxCnT-) - 3D CAD crash course for mechanical enclosures and project housings.
*   [KiCad EDA](https://www.kicad.org/) - The industry-leading, free, open-source PCB design suite. Learn it alongside Phil's Lab tutorials.
*   [Wireshark](https://www.wireshark.org/) - The world's most used network protocol analyser. Essential for networking and security courses.
*   [GDB Tutorial (Beej's Quick Guide)](https://beej.us/guide/bggdb/) - Learn the GNU Debugger. Invaluable for C/C++ and embedded debugging.
*   [Valgrind](https://valgrind.org/) - Memory error detector for C/C++ programs. Catches buffer overflows, memory leaks, and use-after-free.
*   [Tmux Cheat Sheet](https://tmuxcheatsheet.com/) - Reference for the terminal multiplexer you'll use constantly on remote machines and HPC clusters.
*   [Draw.io (diagrams.net)](https://app.diagrams.net/) - Free, browser-based diagramming tool for system architecture, flowcharts, and circuit block diagrams.
*   [Obsidian](https://obsidian.md/) - Free, local-first Markdown note-taking app. Perfect for organising lecture notes, lab books, and project documentation with bidirectional links.
---
 
## 🛠️ Build It: Project Setup & Inspiration
 
*   [EEVblog: How To Set Up An Electronics Lab](https://www.youtube.com/watch?v=R_PbjmGvCAI) - Budget-conscious guide to home lab equipment.
*   [Hackaday](https://hackaday.com/) - The ultimate blog for hardware hacking and engineering projects.
*   [Windows Subsystem for Linux (WSL) Setup Guide](https://learn.microsoft.com/en-us/windows/wsl/install) - Run native Linux on Windows. Essential for FPGA and embedded toolchains.
*   [Raspberry Pi Documentation](https://www.raspberrypi.com/documentation/) - Starting point for IoT, robotics, and embedded Linux.
*   [Build Your Own X (GitHub)](https://github.com/codecrafters-io/build-your-own-x) - Curated list of tutorials for building your own database, OS, shell, game engine, Git, Docker, and more from scratch.
*   [Project-Based Learning (GitHub)](https://github.com/practical-tutorials/project-based-learning) - Massive list of project tutorials organised by language and topic.
*   [Awesome Electronics (GitHub)](https://github.com/kitspace/awesome-electronics) - Curated list of EE resources: CAD tools, PCB fabs, component suppliers, communities, and learning resources.
*   [Instructables: Circuits](https://www.instructables.com/circuits/) - Community-submitted electronics projects with step-by-step instructions.
*   [Hackster.io](https://www.hackster.io/) - Hardware project platform with thousands of community projects using Arduino, Raspberry Pi, FPGA boards, and more.
---
 
## 🎯 Career, CV & Interview Preparation
 
Building skills is half the battle. You also need to know how to present yourself, find opportunities, and perform in interviews.
 
*   [Tech Interview Handbook](https://www.techinterviewhandbook.org/) - Free, comprehensive guide: resume writing, behavioural questions, DSA study plans, and negotiation.
*   [System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer) - Learn how to design large-scale systems. Essential for backend and infrastructure roles.
*   [Levels.fyi](https://www.levels.fyi/) - Compare compensation across companies and roles. Know your worth.
*   [Glassdoor](https://www.glassdoor.co.uk/) - Read interview experiences and questions for specific companies.
*   [GitHub Student Developer Pack](https://education.github.com/pack) - Free tools, cloud credits, and domains for students.
*   [Roadmap.sh](https://roadmap.sh/) - Visual, interactive career roadmaps for frontend, backend, DevOps, AI/ML, and more. Helps you see what to learn and in what order.
*   [STAR Method for Behavioural Interviews](https://www.themuse.com/advice/star-interview-method) - Structure your answers: Situation, Task, Action, Result.
*   [Imperial Careers Service](https://www.imperial.ac.uk/careers/) - Book CV reviews, mock interviews, and find exclusive Imperial-only job listings.
*   [LinkedIn Learning (Free via Imperial)](https://www.imperial.ac.uk/admin-services/ict/self-service/connect-communicate/office-365/features/linkedin-learning/) - Free access to thousands of professional courses through your Imperial account.
*   [Overleaf CV Templates](https://www.overleaf.com/gallery/tagged/cv) - LaTeX CV templates that look clean and professional. Stand out from Word template CVs.
---
 
## 🤝 How to Contribute
 
This is a living document, built by Imperial students, for Imperial students. Contributions are highly encouraged! If you know of a free course, textbook, tool, or repository that helped you land an internship or understand a complex module, please share it.
 
1.  Fork the repository.
2.  Add your resource under the appropriate category.
3.  Submit a Pull Request with a brief note on why the resource is valuable for an EEE/EIE/CS student.
---
 
## ⭐ If this helped you, give the repo a star!
