# NOTE: This site is currently under construction. Please forgive the formatting and writing for now.

# Benjamin Troller

## Personal Info

I'm a third-year Computer Science major at Cal Poly, San Luis Obispo. With any luck, I'll get the classes I need to graduate in June of 2019.

## Personal Projects

### [OTP](https://github.com/btroller/One-Time-Pad)

OTP is a command line C program which pseudorandomly generates [one-time pads](https://en.wikipedia.org/wiki/One-time_pad), as well as encrypts and decrypts data using them. It can take input and give output through redirection or work in place on a given files. 

I intended OTP to be a demonstration of my understanding of C, which I gained from a Systems Programming class. This project is much less involved than some projects we tackled in there. I kept it simple because I wanted it to give a clear demonstration of my proficiency in basic C.

OTP hasn't been thorougly tested as a secure method of communication, so I don't reccomend using it for anything serious. It uses `/dev/random` as a source of random values when generating pads, which is more random than C's `rand()` but still pseudorandom.

To install OTP, clone the repository and run `make`. It uses only the C standard library, so you should be able to simply download it and compile.

## Relevant Classes Taken

## Relevant Class Projects

### Multipeer Voice Chat iOS App

### Battleship Tournament AI
