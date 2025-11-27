# Every Popular Programming Launguage
___
Before we start I should clarify that you are not required to read all of this, because it will get overwelming fast. So I would reccomend starting by reading Under_the_Hood.md then jumping back into chapter 2 and find job you think is interisting then click on the launguage and tools I put as requiremnts on the chapter two. Or skip it and follow the Part V recomindations
___

## Python
> A smart person is fascinated by simplicity not complexety

Python is a compiled launguage, python is probably the simplest programming launguage(Scratch isn't one) and the slowest. Python is loved by his large community and has a LOT of packages yes a LOT there are around 400k packages. That's why python can create a lot of things your entire career can be based on python and his libraries, python is used in data science, backend development, ML development and automation(make boring tasks better). Hello world in python:
```python
print("Hello world") #This is a print function(command) prints Hello world to output. You can write anything between quotes ex: print("Hi")
```
Important Frameworks(A big package):

**Django**: A package that can produce a website

**Numpy**: A package used by data sciensist

Package Manager:

**pip**
___

## Shell
> Everyone was a begineer

Shell isn't actully a programming launguage, but I included it because this might be one of the most important things you will use. Shell or terminal is a set of commands that can be used in every computer by  default for example powershell on windows, most of the commands consist of manipulation of files. The tool shines when you use a cli(command line utility) for example to start a react project or use a package manager, everything can be done in shell, for example claude code an ai coding assistant(more like a thief) that works only in terminal. Even the git technology I write this book with is terminal based. Shell doesn't need frameworks or package managers because it just controls it
___
## HTML
> Society doesn't accept the different one

HTML isn't consideared a programming launguage but for it is. HTML is a markup launguage and uses tags(<>) instead of traditional syntax and it's main function is to structure websites. Hello world in HTML:
```html
<!DOCTYPE html> <!-- Initalazing html-->
<html>  <!-- tag that says its html-->
    <head> <!-- tag that has metadata and other info that doesn't show up on the page-->
        <title>Hello world page</title> <!--Title in the head part-->
    </head>
    <body> <!--tag that displayes stuff on a page-->
        <h1 class="Hello world">Hello World!</h1> <!--A big text a class is for naming a tag for later use-->
    </body>
</html>
```
There isn't a package manager and a framework for html
___
## CSS
> Art is an illusion of opinion

A website needs to look good it helps to gain trust from user, that's where CSS comes in. CSS is a styling programming launguage for HTML. You can't write CSS without HTML. Let's rapresent it by imagining working in powerpoint, you can add headings and paragrphs this is html but when moving objects and changing colors this is CSS. I consider css a difficult launguage because of design standards. CSS can be written inline or in a stylesheet file.
Important Frameworks:

**Sass**: Basicly css but with new features

**Tailwind**: This is a framework that allows to write styles in html classes, highly customizable and has a large community

**Bootstrap**: This is similar to Tailwind but less customizable and fast to write



___
## JavaScript
> More famous you are more haters you have

Javascript is probably the most hated launguage and it has so many versions even a superset(Something like minecraft mods) called typescript, but JS(Short for JavaScript) is the most famous launguage that have a lot of frameworks(Actually in js something like supersets but still in support basic js syntax). A famous person said "Anything that can't be build in javascript will be build in javascript" so you would assume js can make everything but mainly websites. JS is even better with HTML and CSS, an anology based on human anatomy is that HTML is the bone and muscles, JS is organs and brain, CSS is skin and hair. So there are the big three. Hello world in JS:
```javascript
console.log("Hello World") // actually prints it to the browser console(for clarification watch a yt tutorial)
```
Important Frameworks:

React: Made by facebook use componets(reuseble blocks of html and css). Industry standard

Astro: My favourite framework has components, templating system and fast loading(because it sends js to the server site)

Vue: Another component based framework but vue have a lot of useful features by default for example v-if

Angular: Actually typescript based(a js superset). Developed by google has a strong CLI(command line utilites). Uses components

Solid: Similar to react but fast(because compiles the javascript not like react or vue)

Svelte: A small and fast framework has components and reactivity(templating) 

Next.js: It's actually a framework for react adds insane amount of useful features every startup choice

That was a short explanation of the most popular frameworks, they are still a lot(around 10k).

Package managers:
Yeap js community can't even agree what word use for installing a package

npm: The industry standard 

bun: Fast but not popular

deno: Has a lot of unrialized potential

There also npx, yarn and etc... but they are just recycling of the same features(No offense)
___

## C
> High risk high reward

C is one of the most complex usable programming launguages. prefered because of it's speed and control, many programming launguages are made in C. Hello world in C:
```c
#include <stdio.h> // Watch a tutorial if you want to get deeper because is too difficult to explain this
int main() {
   
   printf("Hello, World!");
   return 0;
}
```
I'm not reccomending it as a first programming launguage but do whatever you want

___

## Rust
> Safety first performance second

Rust is fast but difficult something like C but it is one of the most fast coding launguages that is also safe(memory safe). Hello world in rust:
```rust

fn main() {
    println!("Hello, World!");
}
```
Important Frameworks:
**Rocket**: A backend web framework
**Actix**: Another backend web framework
Package Manager:
**Cargo**: Rust's official package manager
___

## Cobol
> Old is gold

COBOL is one of the oldest programming launguages still in use today. Mainly used in banks and goverment institutions. Hello world in COBOL:
```cobol
       IDENTIFICATION DIVISION.
       PROGRAM-ID. HelloWorld.
       PROCEDURE DIVISION.
           DISPLAY 'Hello, World!'.
           STOP RUN.
```
Important Frameworks:
There aren't any popular frameworks for COBOL
Package Manager:
There isn't any popular package manager for COBOL
___

## Java
> Write once, run anywhere

Java is a versatile and widely-used programming language known for its portability, performance, and robustness. It is designed to be platform-independent, allowing developers to write code that can run on any device with a Java Virtual Machine (JVM). Hello world in Java:
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
Important Frameworks:
**Spring**: A comprehensive framework for building enterprise-level applications, particularly web applications and microservices.
**Hibernate**: An object-relational mapping (ORM) framework that simplifies database interactions by mapping Java objects to database tables.
Package Manager:
**Maven**: A popular build automation and dependency management tool for Java projects.

Fun fact, netflix uses java for his backend services
___

## C++

> Performance is key

C++ is an extension of the C programming language that adds object-oriented programming features and other enhancements. It is known for its performance, efficiency, and flexibility, making it a popular choice for system programming, game development, and high-performance applications. Hello world in C++:
```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

Important Frameworks:
**Qt**: A cross-platform framework for developing graphical user interfaces (GUIs) and applications.
**Boost**: A collection of libraries that provide additional functionality for C++ programming, including data structures, algorithms, and utilities.
Package Manager:
**Conan**: A popular package manager for C++ that simplifies dependency management and builds processes
___

## C#

> Simplicity and power combined

C# (pronounced C-sharp) is a modern, object-oriented programming language developed by Microsoft as part of the .NET framework. It is designed for building a wide range of applications, from desktop and web applications to mobile apps and games. Hello world in C#:
```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, World!");
    }
}
```
Important Frameworks:
**.NET**: A comprehensive framework for building various types of applications, including web, desktop, and mobile applications.
**Unity**: A popular game development engine that uses C# for scripting and building interactive 2D and 3D games.
Package Manager:
**NuGet**: The official package manager for the .NET ecosystem, used for managing libraries and dependencies in C# projects.
___

## Go
> Efficiency meets simplicity

Go (also known as Golang) is a statically typed, compiled programming language developed by Google. It is designed for simplicity, efficiency, and scalability, making it a popular choice for building web servers, networking tools, and cloud-based applications. Hello world in Go:
```go
package main
import "fmt"
func main() {
    fmt.Println("Hello, World!")
}
```
Important Frameworks:
**Gin**: A high-performance web framework for building RESTful APIs and web applications.
**Beego**: A full-featured web framework that provides tools for building web applications, including routing, ORM, and session management.
Package Manager:
**Go Modules**: The official dependency management system for Go, used for managing packages and versions in Go projects.
___
## PHP
> Web made easy

PHP is a popular server-side scripting language designed for web development. It is widely used for creating dynamic web pages and applications, and it can be embedded directly into HTML code. Hello world in PHP:
```php
<?php
echo "Hello, World!";
?>
```
Important Frameworks:
**Laravel**: A powerful and elegant web framework that provides tools for building modern web applications, including routing, ORM, and authentication.
**Symfony**: A flexible and modular web framework that offers reusable components for building web applications and APIs.
Package Manager:
**Composer**: The official package manager for PHP, used for managing libraries and dependencies in PHP projects.
___

## Ruby
> Developer happiness first

Ruby is a dynamic, object-oriented programming language known for its simplicity and productivity. It is often used for web development, particularly with the Ruby on Rails framework. Hello world in Ruby:
```ruby 
puts "Hello, World!"
```
Important Frameworks:
**Ruby on Rails**: A popular web framework that follows the convention over configuration principle, making it easy to build web applications quickly.
**Sinatra**: A lightweight web framework for building simple web applications and APIs with minimal effort
Package Manager:
**RubyGems**: The official package manager for Ruby, used for managing libraries and dependencies in Ruby projects.
___
## SQL
> Data is the new oil
SQL (Structured Query Language) is a specialized programming language designed for managing and manipulating relational databases. It is used to perform various operations on data stored in databases, such as querying, inserting, updating, and deleting records. Hello world in SQL:
```sql
SELECT 'Hello, World!' AS Greeting;
```
Important Frameworks:
There aren't any popular frameworks for SQL
Package Manager:
There isn't any popular package manager for SQL
___

## Assembly
> Close to the metal
Assembly language is a low-level programming language that is closely related to machine code. It provides a way to write instructions that can be directly executed by a computer's CPU. Assembly language is specific to a particular computer architecture and is often used for performance-critical applications, embedded systems, and low-level programming tasks. Hello world in Assembly (x86 architecture):
```assembly
section .data
    msg db 'Hello, World!', 0
section .text
    global _start
_start:
    ; write our string to stdout    
    mov eax, 4          ; syscall number for sys_write
    mov ebx, 1          ; file descriptor 1 is stdout
    mov ecx, msg        ; pointer to our message
    mov edx, 13         ; length of our message
    int 0x80            ; call kernel
    ; exit
    mov eax, 1          ; syscall number for sys_exit
    xor ebx, ebx        ; exit code 0
    int 0x80            ; call kernel
```
Important Frameworks:
There aren't any popular frameworks for Assembly
Package Manager:
There isn't any popular package manager for Assembly
___

## Binary
> The language of machines
Binary code is the most fundamental form of programming language, consisting of only two symbols: 0 and 1. It is the language that computers use to represent and process data at the lowest level. Binary code is used to encode instructions, data, and other information that can be understood and executed by a computer's CPU. Hello world in Binary (ASCII representation):
``` 01001000 01100101 01101100 01101100 01101111 00101100 00100000 01010111 01101111 01110010 01101100 01100100 00100001
```
```
Important Frameworks:
Basically all programming launguages are frameworks for binary
Package Manager:
There isn't any popular package manager for Binary
___ 
## TL;DR 
There are a lot of programming launguages, each one is made for a specific task.
Some launguages are easy to learn but slow(Python), some are difficult but fast(C, Rust).
Some launguages are made for web development(HTML, CSS, JS), some for system programming(C, C++).
Choose the right launguage for your task and have fun coding!