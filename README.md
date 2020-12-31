# Quine 

Quine is a program whose output is the exact same program ie. self - replicating program.

Here I have made a quine.cpp file which is a quine in C++

## Installation

You will require the g++ compiler to compile the C++ program. If you have it then skip. 

Else run on the terminal
```bash 
$ sudo apt install g++
```

## Usage

cd to the location of quine.cpp
Then run

```bash
$ g++ -std=c++14 -o quine quine.cpp
$ ./quine > nameofoutputfile.txt
```
You'll get the output in a file nameofoutputfile.txt