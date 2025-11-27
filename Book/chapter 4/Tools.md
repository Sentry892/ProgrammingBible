# Tools of a programmer
____

You know about programming launguges but how can we actually write code deploy it and test it. In this chapter we will cover code editors, deployment tools, version control tools, other utilites and at the you will find my workflow that is very efficient and customizeaable.

___

## Where to write code
> A nokia is a phone but we use smartphones

You can write code everywhere even on paper, to execute a file of code you just need the code in text(preferably) and the file exestension for example .python, but actual developers use text editors/code editors, those are programs that help you write text(in our case code), many of them have a lot of timesaving and navigation systems the most famous one is VScode(This is written in Vscode), developed by minecrosoft has a lot of auto complition and utility tools if you want to start coding choose VScode because it supports every launguage and has an crazy amount of extensions and themes. Mastering VScode will turn you into a coding machine(for example I wrote this entire chapter without touching my mouse), many also use a IDE(integrated development envioroment) made for one programming lunguage in specific for example pycharm a famouse IDE for python. There other code editors like subline text, webstorm, cursor(keep that in mind), windsurf and Xcode(for app development). There also code editors that are made for people that don't have a life and are scared of a mouse like vim, nvim(That one is peak), emacs, nano they are light weight and made for productivity.

___

## Version Control
> Save your work

Version control is when you save your work/files in cloud. The most popular is git that works like a tree, for example branches and etc. Git helps developer to control and save previous updates of code(Think of it like CTRL+Z but advenced). You can find open-source(The code is posted online and it's free) git projects on github. There a lot of utilites for git since it is only a command line tool, but most of them are enabled by default in a code editor/IDE.
### Crash course on git
To start a git tree you should get into your  projects folder and type **git init** after initialazing your project next make changes in your project and write **git add .** this command adds all the changes to the scene that changes can be deleted from the scene then write **git commit -m "-m means message and you need to write your message in this strings"** and then write **git push** it could ask you for your github credentials.
___

## Terminals
> Every programming legend begins with a terminal command

Every OS has it's own terminal but you should add a linux terminal to your OS, before that what is a terminal? A terminal is an admin panel for your computer it can be used to control your OS entirely, most dev tools are build for terminal since it doesn't require any UI/UX. An example of a dev tool on terminal is git or the astro setup wizard.
___
## Ai tools
> The brightest stars are born in darkerst nights

Usually I'm against vibe-coding(I will explain this in a second) but I feel that begineers should have some expirience working with ai tools. Vibe coding is a practice of developers using Ai tools to write their code instead of manually do it. First I'm gonna adress a famous question: "Will AI take programming jobs?", simple answear not, difficult one is that AI is literally made and trained by humans but even if you aren't a machine learning expert you need to understand that nobody in there sane mind would give important databases or code files to AI since one hallunation and your database is dead, this actually happend before and proves that AI tools for the next 20-30 years will not replace human programmers, talking about long term; AI companies will go broke fast, let me explain: To train a model similar to chatgpt 4 will require the budget of millions maybe billions, it will be insanly difficult to cover up those costs and make returns for investors(THey originaly give money to AI companies). But as for right now AI is an extremly powerful tool that can save you time, so here are two main types of AI coding tools: 

1. AI code editors, a code editor with an AI chat built in(normally a vs code clone), examples: Antigravity from google(I just discover they have like 3 editors, stop milking dawg), cursor(A bit weak lately but my favourite), windsurf(Never tried it) and etc...

2. CLI tools, write claude in terminal a chat pops up made for developers that have their editor of preferance, examples: claude cli(A good one but the bills will take away your house in seconds), google cli(Actually free), codex(never tried) and etc.. This one is a popular niche clap some print togheter and add an api(signal to the AI in this context) call when hit enter and you made a cli tool

Since this is targeted towards begineers you should not over rely on AI remember it's just a companion
___

## Deployment tools
> Show the world your creation

After writing code you need to deploy it(deployment is when you upload your code to a server so other people can access it). There are a lot of deployment tools for example: netlify, Vercel, Heroku, GitHub pages and etc... My personal favorite is Netlify because it has a lot of features for free and easy to use, but if you are using a framework like next.js or react Vercel is the best choice since it is made by the same team that made next.js so it has a lot of optimizations for it. For backend deployment I recommend heroku since it is easy to use and has a lot of free features.
___
## Containerization tools
> Pack your stuff like a pro

Containerization is a process of packaging an application and its dependencies into a container so it can be run on any system. The most popular containerization tool is Docker, it allows you to create, deploy, and run applications in containers. Containers are lightweight and portable, making them ideal for development and deployment. Another popular tool is Kubernetes, which is used for automating the deployment, scaling, and management of containerized applications. If you are working on a project that requires multiple services or microservices, containerization tools like Docker and Kubernetes can help you manage and deploy your application efficiently.
___
## Monorepos
> One repo to rule them all

Monorepos are a way of organizing codebases where multiple projects or packages are stored in a single repository. This approach can simplify dependency management, code sharing, and collaboration among teams. Popular tools for managing monorepos include Nx, Lerna, and Turborepo. These tools provide features like dependency graph management, build optimization, and task running to help developers work efficiently in a monorepo setup. An example of a monorepo is Google's codebase, which contains the code for many of their products in a single repository. Monorepos can be beneficial for large teams and projects, but they also come with challenges like increased complexity and potential performance issues. It's important to evaluate whether a monorepo is the right choice for your project before adopting this approach.
___
## Distributing data
> Share your data with the world

Distributing data is an important aspect of modern applications, especially when dealing with large datasets or real-time data. Popular tools for distributing data include Apache Kafka, RabbitMQ, and AWS Kinesis. These tools allow you to stream data between different services and applications, enabling real-time processing and analysis. For example, Apache Kafka is widely used for building real-time data pipelines and streaming applications, while RabbitMQ is a message broker that facilitates communication between different components of a system. When choosing a data distribution tool, consider factors like scalability, reliability, and ease of integration with your existing infrastructure.
___
## My workflow
> Work smart, not hard

My workflow is designed to maximize productivity and minimize distractions. Here are the steps I follow: First I use Arch Linux as my operating system because it is lightweight and customizable(and I have no job). As my code editor I use Antigravity AI code editor but Cursor is also a great choice. For code testing I use CodeRabbit(Please sponsor me). For version control I use Git with GitHub for remote repositories. I write my code in a terminal using kitty terminal. For deployment I use Netlify for since I mainly do frontend projects and also manual setup features. For containerization I use Docker to package my applications and their dependencies. I also use Nx for managing monorepos, which helps me keep my projects organized and efficient. I platforms like google ads for promoting my freelance projects. This workflow allows me to stay focused and get more done in less time. My tech stack may change over time as new tools and technologies emerge, but the core principles of productivity and efficiency will always remain the same: 
1. Astro/React for frontend 
2. Node.js/Supabase for backend
3. Next.js for fullstack projects
4. Three.js for 3D UI
5. Tailwind CSS for styling
6. Netlify for deployment
__
## API
> Talk is cheap. Show me the code.
To finish it off I will explain what an API is. An API(application programming interface) is a set of rules and protocols that allows different software applications to communicate with each other. APIs define how requests and responses should be formatted, what data can be accessed, and what actions can be performed. APIs are used in a wide range of applications, from web development to mobile app development to cloud computing. For example, when you use a social media app on your phone, the app communicates with the social media platform's API to retrieve your feed, post updates, and interact with other users. APIs can be public or private, depending on whether they are intended for use by external developers or only within a specific organization. Popular examples of public APIs include the Twitter API, Google Maps API, and OpenWeatherMap API. Overall, APIs are a crucial component of modern software development, enabling developers to build complex applications that leverage the functionality of existing services and platforms.