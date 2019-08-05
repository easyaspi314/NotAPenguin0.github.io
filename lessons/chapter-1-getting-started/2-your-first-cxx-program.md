# Chapter 1-2: Creating your first C++ program



#### Hello world!

Traditionally, the first program in a language a person write is a 'Hello World' program. So, we're going to do the same. First, we're going to need a place to write our code. For this tutorial, we are going to use an online compiler in the beginning. We are doing this because build systems are complicated, and we want to simplify the process a little bit. 

There are a lot of online compilers out there. You can choose whichever you want of course, but I recommend you use [Coliru](https://coliru.stacked-crooked.com/). Here are a few other online compiler tools worth noting:

- [Wandbox](http://wandbox.org)
- [Godbolt](http://godbolt.org)

#### The code

And finally, here it is: Your first ever C++ program!

```cpp
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
```

If you copy and paste this in an online editor and run the program, you should see that it prints

```
Hello World!
```

Let's break this program down line by line.

```cpp
#include <iostream>
```

This first line tells the compiler to include the `iostream` library. This is a part of the C++ Standard Library, a big set of functionality already there for you to use. The `iostream` library is used for input and output via the console. 

```cpp
int main() {
```

This line marks the start of the `main` function. Every program needs one. When your program starts, this is where execution begins.

```cpp
std::cout << "Hello World!";
```

Perhaps the most complicated line in the program. This is the line of code that effectively writes the output. `std::cout` is the *standard output stream* (`cout` stands for *character output*). This *standard output stream* is usually linked to the console. To write data to the console, we use the `<<` operator. After the `<<` comes the data we want to write, in this case `"Hello World!"`. Finally, we end our line with a semicolon (`;`). This is because C++ expects a semicolon to come after every *statement*. Don't worry which lines represent statements and which don't for now. 

```cpp
return 0;
```

This marks the exit of our program. `return` means we exit the `main()` function, and `0` is the exit code. By convention, an exit code of `0` means success, while any other value means failure.

```cpp
}
```

This is the final line of our program. It marks the exit of the `main()` function.



And that's it for writing a "Hello World" program in C++. Feel free to modify the program as you wish. Can you try to make it print `"Hello Humans"` instead? [Solution](solutions/hello-humans.html)

[Previous](1-what-is-a-program.html) 																																			[Next]()

[back to homepage](../../../index.html)

