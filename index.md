# Personal Info

I'm a third-year Computer Science major at Cal Poly, San Luis Obispo. With a little luck at registration time, I'll graduate in June of 2019.

I generally enjoy making programs that run as efficiently as possible -- that feeling you get when finding a good solution is what I like most about software engineering. I'm experienced with Windows, Mac (my favorite), and Linux environments. I can efficiently use Vim if needed, but I've recently taken a liking to Xcode for its helpful editing features.

Github: [btroller]() LinkedIn: [btroller](https://www.linkedin.com/in/btroller/) Keybase: [invener](https://keybase.io/invener) Email: [btroller@calpoly.edu](mailto:btroller@calpoly.edu)

# Personal Projects

## [OTP](https://github.com/btroller/One-Time-Pad)

OTP is a command line C program which pseudorandomly generates [one-time pads](https://en.wikipedia.org/wiki/One-time_pad), as well as encrypts and decrypts data using them. It can take input and give output through file redirection or work in place on given files. 

I intended OTP to be a demonstration of my understanding of C, which I gained from a Systems Programming class. This project is much less involved than some projects we tackled in there. I kept it simple because I wanted it to give a clear demonstration of my proficiency in basic C.

OTP hasn't been thorougly tested as a secure method of communication, so I don't reccomend using it for anything serious. It uses `/dev/random` as a source of random values when generating pads, which is more random than C's `rand()` but still pseudorandom.

To install OTP, clone [its repository](https://github.com/btroller/One-Time-Pad) and run `make`. It uses only the C standard library, so you should be able to simply download it and compile. Documentation is available in the `Readme.md` included in the repository.

# Notable Class Projects

## [Intro to Software Engineering — Super CSC FighterZ](https://github.com/TraceRainbolt/SuperCSCFighterZ) (under active development)

A project I'm currently working on with a team of six others. We're making a game based on professors in the Cal Poly Computer Science Department.

The game will support single player and local multiplayer modes with a selection of fighters.

## [Mobile App Development — Multipeer Voice Chat iOS App](https://github.com/btroller/Multipeer-Voice-Chat)

I developed a simple peer-to-peer voice chat app using Apple's `MultipeerConnectivity` and `AVFoundation` frameworks in Swift. Core functionality is present now, but I plan to make it more complete in the future.

The app allows up to 8 devices to trasmit and play back each others' audio at the same time. It works with fairly minimal lag, which I plan to reduce further in the future.

I plan to make a Mac app counterpart, as these framworks are cross-platform and I'm also interested in development for macOS.

## Systems Programming — Battleship Tournament AI

In CPE 357, we were given an assignment for extra credit to develop a battleship player in C. Unfortunately, I can't give the source code for this project because I'll get in trouble if someone copies my work. However, I can say that I tied for first place in a tournament between Battleship players submitted in all of my professor's CPE 357 sections. I based my player heavily on the suggestions of Nick Berry in [his post on the DataGenetics blog](http://www.datagenetics.com/blog/december32011/).

## [Professional Responsibilities — Term Paper](https://github.com/btroller/CSC-300-Paper)

I wrote a thoroughly-sourced 4000-word paper on the ethics of Samsung's decision to issue updates to disable Note 7s in late 2016 and early 2017. This paper is written in LaTeX with a bibliography done in BibTeX. A repository containing the source code and the compiled PDF of the paper can be found [here](https://github.com/btroller/CSC-300-Paper).

# Relevant Classes Taken

* CSC 357: Systems Programming (ANSI C and low-level UNIX/Linux development)
* CSC 436: Mobile Application Development (iOS Development with Swift)
* CSC 349: Design and Analysis of Algorithms
* CSC 348: Discrete Structures (Logic, Proofs, and Structures)
* CSC 315: Computer Architecture (MIPS Assembly and hardware design of CPUs)
* CSC 300: Professional Responsibilities
* CSC 225: Introduction to Computer Organization (LC-3 Assembly and C)
* CSC 103: Fundamentals of Computer Science III (Data Structures and algorithm analysis in Java)
* CSC 102: Fundamentals of Computer Science II (Object-oriented programming in Java)
* CSC 101: Fundamentals of Computer Science I (Python)

### Currently Enrolled In

* CSC 307: Introduction to Software Engineering (Agile development in Java with best practices)
* CSC 453: Introduction to Operating Systems (primarily MINIX)
* CSC 445: Theory of Computation

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
