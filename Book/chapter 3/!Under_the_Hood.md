# Under the Hood

> "Everything is theoretically impossible, until it is done." 

___
So what is a programming language, how does the computer understand it, why are there so many rules and syntax to follow, and what happens when you run your code? In this chapter, I will explain everything that happens when running print("Hello, World!"). Also, in this chapter you will find a programming encyclopedia that will help you discover different programming languages and their uses.
___
## Programming Languages & Compilers
A programming language is a translation system that converts human-readable code into machine code (binary: ones and zeros) that a computer can understand. You can ask a logical question: why are there so many programming languages? The answer is simple: different programming languages are designed for different purposes and preferences. For example, Python is known for its simplicity and readability, making it a great choice for beginners and data science (but it's not the fastest language). On the other hand, C and C++ are powerful languages that provide low-level access to memory and system resources, making them ideal for system programming and performance-critical applications. There are two main approaches to translating code into machine code: compilation and interpretation. A compiler is a program that translates the entire source code of a programming language into machine code before execution. This means the entire program is converted into a standalone executable file that can be run on any compatible system without the need for the original source code or compiler. Examples of compiled languages include C, C++, and Rust. An interpreter, on the other hand, translates and executes the source code line by line at runtime. The interpreter reads each line of code, translates it into machine code, and immediately executes it. Examples of interpreted languages include Python, JavaScript, and Ruby. Some languages use a combination of both compilation and interpretation, such as Java, which compiles source code into an intermediate bytecode that is then interpreted by the Java Virtual Machine (JVM). But why do we need compilers and interpreters? The answer is that compiled languages are generally faster in execution but can be more difficult to debug, while interpreted languages are usually easier to debug but slower in execution. So the choice between compiled and interpreted languages depends on the specific requirements of the project, such as performance, development speed, and ease of debugging.
All languages have their own AST (abstract syntax tree), which is similar to grammar rules in human languages. For example, in Python you can't just write:
```python
# the wrong way
If 5 is a number print("Yes")
# the correct way
num = 5  # A variable assignment like pi in mathematics
if type(num) == int:  # Checking the type of variable for integer (number)
    print("Yes")  # writing output to the console
```
We can't write the wrong way because Python has its own AST rules that we have to follow. This is like grammar rules: in English we can't write "Age of John is how much?"; instead we write "How old is John?".

___

## OS & Virtual Machines
An operating system (OS) is a big thing in coding. It is the software that manages all of the hardware and software on a computer. It acts as an intermediary between the user and the computer hardware, providing a user-friendly interface (unless it's Arch) and managing system resources such as memory, processing power, and storage. There are several operating systems available. The most popular ones are Windows (spyware), macOS (only for Apple devices), and Linux, which is actually just a kernel (the blueprint of an OS). That's why there are so many distros (versions) of Linux, like Ubuntu (easy to use), Kali Linux (for hackers and kids who want to feel like hackers), and Arch Linux (for advanced users who want to customize everything and have no job, of course). Each operating system has its own strengths and weaknesses, and the choice of which one to use often depends on personal preference, hardware compatibility, and specific use cases. For example, many servers run on Linux because it is open source (code available for free) and generally more secure than Windows. On the other hand, macOS is popular among creative professionals because of its user-friendly interface and powerful software applications for design, video editing, and music production. Overall, the operating system is a crucial component of any computer system, and it plays a vital role in ensuring that the hardware and software work together seamlessly to provide a smooth user experience. Developers can use whatever OS they want, but many prefer Linux because of its flexibility and the tools that come with it. Also, most servers run on Linux-based OSes(I wasted 30 minutes to understand how to spell it) because of their security and open-source nature. You can also use virtual machines (software that emulates a computer system) to run different operating systems on your computer without needing to install them directly. This is useful for testing software, running multiple operating systems on a single machine, and isolating potentially harmful applications from the host system. Popular virtual machine software includes VirtualBox, VMware, and Hyper-V. If you are interested in learning more about Linux, you can check out Linux Mint's official website or Ubuntu's official website.
___
## Clouds & Containers
I talked about **servers**. A server is a computer (usually powerful) that provides data, resources, or services to other computers over a network, typically the Internet. Servers can host websites, store files, run applications, and manage databases, among other functions. They are designed to handle multiple requests simultaneously and provide reliable access to resources for users and devices connected to the network. Servers can be physical machines located in data centers or virtual servers hosted in the cloud. Not everybody can afford a physical server, so cloud computing is the solution. The cloud is a network (a lot of computers connected together) of remote servers hosted on the Internet to store, manage, and process data, rather than using a local server or personal computer. Cloud computing allows users to access computing resources on demand, without the need for physical hardware or infrastructure. Developers use cloud services like AWS, Google Cloud, and Microsoft Azure to deploy and manage their projects because it is cost-effective (until you are in debt because you forgot to turn off your server), scalable, and flexible. They use containers to package their code files and dependencies (you will learn about this later) into a single unit that can run consistently across different environments (computers). In simple words, containers in coding are like containers in real life: a real-life container is used to transport goods easily and safely and to connect different modes of transportation like ships, trucks, and trains. Similarly, in coding, a container packages an application and its dependencies into a single unit that can be easily transported and run on different computing environments without worrying about installing anything. Popular containerization platforms include Docker and Kubernetes (more on that in the tools chapter).

___

## Components Of a Programming Language
In a programming language there are four main components: syntax (includes AST), compiler/interpreter, package manager, and dependencies. We covered the first two, but what are the others? A dependency (also called a library, framework, or package) is someone else's code that can be installed. Installation happens through a package manager, which is an official or third-party tool that installs packages (someone else's code). For example, if you want to code a dice in Python, first you might download the package (probably already installed):
```python
pip install random
```
Here we installed random package using pip(python's package manager)
```python
import random  # importing the package
x = random.randint(1, 6)  # x is a number from 1 to 6
print(x)  # writing the output
```

___
## TL;DR
Programming languages are just different dialects for telling your computer what to do.  
Compilers translate everything at once, interpreters translate on the fly.  
OSes run the show, clouds host your stuff, and containers make sure your app runs anywhere.  
Everything else? Just humans trying to make computers less angry.
___
