# Chapter 1-1: What is a program?

####  Introduction

So, you decided to learn C++. Great! But before we get to writing code, we first have to understand what a program *actually* is, and how the computer goes from source code to producing an actual executable program. 

*Note: This might seem like a boring topic, but it is a very important one. Try to work through it anyway, even if you can't wait to get started with coding*

#### Source code

The whole process of creating a program of course starts by writing code. A very basic C++ program looks a bit like this:

```cpp
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
```

Don't worry if this doesn't make a lot of sense right now. What's important is that we have source code in the form of a text file, and that we are going to transform it into an executable program. The first step when doing this is the compiler.

#### Meet: The compiler

Very simply said, the compiler is a program that converts source code into a program We call this process *compiling*. The compiler takes a set of source files as inputs, and outputs an executable program. This is the main stage of your building process. There is also a final stage known as *linking*, but more on that later.

And that's it! In the next lesson, we are going to put this lesson into practice and create our very first C++ program.

[Next](2-your-first-cxx-program.html)

[back to homepage](../../../index.html)

