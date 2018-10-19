# Personal Info

I'm a senior-year Computer Science major at Cal Poly, San Luis Obispo. I expect to graduate in June of 2019.

I'm experienced with Mac (my favorite), Windows, and Linux environments. I've used a whole variety of tools and software, including Git, SVN, Valgrind, Vim, and Xcode, to namedrop a few.

I've liked the systems-level programming I've done so far and am interested in security, but I also enjoy iOS app development and want to look into Mac app development.

### Links
Github: [btroller](https://github.com/btroller) LinkedIn: [btroller](https://www.linkedin.com/in/btroller) Keybase: [invener](https://keybase.io/invener) Email: [btroller@calpoly.edu](mailto:btroller@calpoly.edu)

# Personal Projects

## [OTP](https://github.com/btroller/One-Time-Pad)

OTP is a command line C program which pseudorandomly generates [one-time pads](https://en.wikipedia.org/wiki/One-time_pad), as well as encrypts and decrypts data using them. It can take input and give output through file redirection or work in place on given files. 

I intended OTP to be a demonstration of my understanding of C, which I gained from a Systems Programming class. This project is much less involved than some projects we tackled in there. I kept it simple because I wanted it to give a clear demonstration of my proficiency in basic C.

OTP shouldn't be used for anything serious. It uses `/dev/random` as a source of random values when generating pads, which is more random than C's `rand()` but still pseudorandom. However, if you have a [source of truly random data](https://en.wikipedia.org/wiki/Hardware_random_number_generator) available to you, you can still use OTP to encrypt and decrypt data using that truly random data as a one-time pad.

# Notable Class Projects

## Senior Project — LC-3 Simulator for macOS

This project is in its early stages, but I plan to write a native Mac version of an LC-3 simulator. I expect this to be useful to students at Cal Poly and other schools who are learning the LC-3 architecture while using Macs. In my experience, they typically resort to using the web-based simulator written by a former Cal Poly student. This works well enough, but I think I can improve the experience for students using Macs significantly.

I expect to generally recreate the commonly-used Windows version of the simulator and go from there.

## [Intro to Software Engineering — Super CSC FighterZ](https://github.com/TraceRainbolt/SuperCSCFighterZ)

Super CSC FigherZ is a game I developed with a team of [six others](https://github.com/TraceRainbolt/SuperCSCFighterZ/graphs/contributors). It allows you to fight as two professors in the Cal Poly Computer Science Department, Davide Falessi and Kurt Mammen.

## [Mobile App Development — Multipeer Voice Chat iOS App](https://github.com/btroller/Multipeer-Voice-Chat)

I developed a simple peer-to-peer voice chat app using Apple's `MultipeerConnectivity` and `AVFoundation` frameworks in Swift. Core functionality is present now, but I plan to make it more complete in the future.

The app should (I haven't tested with more than 2 devices yet) allow up to 8 devices to trasmit and play back each others' on-device microphone-captured audio at the same time. It works with fairly minimal lag, which I plan to reduce further in the future.

I plan to make a Mac app counterpart, as these framworks are cross-platform and I'm also interested in development for macOS.

## Systems Programming — Battleship Tournament AI

In Systems Programming, students were given an assignment for extra credit to develop a [battleship](https://en.wikipedia.org/wiki/Battleship_(game)) player in C. The project required students to write a program that would interface with a tournament-managing program through pipes, receiving information about the board and sending requests for shots to be made. 

Unfortunately, I can't give the source code for this project because I'll get in trouble if someone copies my work. However, I can say that I tied for first place in a tournament between Battleship players submitted in all of my professor's CPE 357 sections. I based my player heavily on the suggestions of Nick Berry in [his post on the DataGenetics blog](http://www.datagenetics.com/blog/december32011/).

## [Professional Responsibilities — Term Paper](https://github.com/btroller/CSC-300-Paper)

I wrote a thoroughly-sourced 4000-word paper on the ethics of Samsung's decision to issue updates to disable Galaxy Note 7s in late 2016 and early 2017. The paper is written in LaTeX with a bibliography done in BibTeX. The linked repository contains the source code and a compiled PDF of the paper.

# Relevant Classes Taken

* CSC 307: Introduction to Software Engineering (Agile development in Java with best practices)
* CSC 453: Introduction to Operating Systems (primarily MINIX)
* CSC 445: Theory of Computation (theory of formal languages and automata)
* CSC 357: Systems Programming (ANSI C and low-level UNIX/Linux development)
* CSC 436: Mobile Application Development (iOS Development in Swift)
* CSC 349: Design and Analysis of Algorithms
* CSC 348: Discrete Structures (Logic, Proofs, and Structures)
* CSC 315: Computer Architecture (MIPS Assembly and hardware design of CPUs)
* CSC 300: Professional Responsibilities
* CSC 225: Introduction to Computer Organization (LC-3 Assembly and C)
* CSC 103: Fundamentals of Computer Science III (Data Structures and algorithm analysis in Java)
* CSC 102: Fundamentals of Computer Science II (Object-oriented programming in Java)
* CSC 101: Fundamentals of Computer Science I (Python)

### Currently Enrolled In

* CSC 430: Programming Languages I
* CSC 321: Introduction to Computer Security
* CSC 365: Introduction to Database Systems
* CSC 491: Senior Project I

# Technologies Known

## Languages

* C
* Swift
* Java
* Python

## Tools

* Git
* SVN
* Valgrind
* LaTeX (also a language, I know)
* Vim
* Xcode
