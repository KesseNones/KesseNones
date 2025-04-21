# 👋 Greetings! 
# 📚 About 

I am Jesse, a computer science degree holder looking for an opportunity to apply the skills I've learned in frontend and backend software engineering through my experience with Seasalt.ai and my undergraduate degree program. Though I may have the most experience with those two aspects of software engineering, I am open to learning about other areas of software development such as cyber-security or AI/Machine Learning. I enjoy programming languages and systems programming concepts. When not coding, I play video games, write my own sci-fi lore, learn about the universe, and more. 
#### 🔍 Fun Fact 
I made **two** whole programming languages on my own just because I can!
# 📜 Programming Languages 
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
- ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
- ![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=for-the-badge&logo=haskell&logoColor=white)
- ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
- ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
- ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
- ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sql&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
# 🔧 Tools 
- ![Agile](https://img.shields.io/badge/Agile-FFFFFF?style=for-the-badge&logo=agile&logoColor=black)
- ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
- ![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)
- ![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
- ![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
- ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
- ![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)
- ![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-0E1128?style=for-the-badge&logo=unreal-engine&logoColor=white)
- ![Overleaf](https://img.shields.io/badge/Overleaf-47A141?style=for-the-badge&logo=overleaf&logoColor=white)
- ![Obsidian](https://img.shields.io/badge/Obsidian-483699?style=for-the-badge&logo=obsidian&logoColor=white)
# 💻 Projects 
## [Lmao Programming Language](https://github.com/KesseNones/LmaoProgrammingLanguage)
Uses the Rust programming language to carry out running the Lmao programming language. 

This project features both an interpreter and a compiler for Lmao. 

The interpreter takes in a `.lmao` file, parses it into an abstract syntax tree, and runs it all in one go. 

The compiler takes a `.lmao` file, parses it, turns it into an abstract syntax tree, translates the ast into a Rust file, then lastly uses rustc to compile it to machine code as an executable. This results in a language faster than Python when compiled!

This project greatly improved my understanding of Rust and how to optimize the underlying language it interprets and is still in active development which has been really fun.

## [EcksDee Programming Language](https://github.com/KesseNones/EcksDee-Programming-Language)
The predecessor to Lmao that uses Haskell for both interpretation and compilation of `.xd` files. 

This project originated as a crude Forth dialect made for a programming language design class in my undergraduate university program. Unsatisfied with such a basic implementation, I took the foundations and built upon them until EcksDee contained features held by practically every modern programming language.

The interpreter works just like Lmao but with Haskell. 

The compiler works the same as with Lmao just with Haskell and ghc instead of the Rust equivalents.

The project overall was my first forray into using advanced functional programming concepts to implement a programming language well beyond the scope of the university class the initially crude Forth dialect orignated in. This also gave me a vastly greater understanding of Haskell itself via the usage of Monads to allow for side effects and IO.

## [Receipt Processor](https://github.com/KesseNones/FetchBackendExercise)
A project created for Fetch as part of their backend exercise. It utilizes the Go programming language to implement HTTP endpoints that can be queried using curl or other tools such as web browsers. 

This project employs Docker to build and run the server in a containerized environment, making it more usable across platforms, 
provided the host has a recent Docker version installed. 

The endpoints implemented are `/receipts/process` and `/receipts/{id}/points`.

`/receipts/process` takes a POST request that contains a receipt JSON. This JSON is parsed by the server to determine how many 
points it's worth, based on a set of arbitrary rules provided by Fetch. This point value is then stored in a hashmap with a generated
UUID as the key and the calculated points as the value. This database is stored in memory because Fetch instructed it to be that way.
Once stored, a JSON containing the generated ID is returned to the user like so: `{"id": "23423d-23dd2-d23d-23d-23dddd"}`.
If the receipt is formatted wrong in some way, an error is returned to the user.

`/receipts/{id}/points` takes a GET requst with the URL containing a generated ID. If this ID is valid, it is used to query
the hashmap to find the point value associated with the key. If the key exists, a JSON containing the number 
of points associated with that ID is returned like so: `{"points": 42}`.
If the ID doesn't exist, an error is returned to the user indicating as such.

This project gave me a significant improvement to my understanding of Docker and is a good showcase of my understanding of basic HTTP endpoints to access pseudo-databases. 

## [Omniprogram Side Projects](https://github.com/KesseNones/Omniprogram-Side-Projects)
An old repo containing more than 100 GUI Python programs that are all linked together through calls to program mains. This effectively results in a large program that can perform dozens of different tasks, mostly time related. 

This repo is rarely updated with the exception of the occasional fix but it's still a fun set of GUI programs. Windows users can also run this without Python since an executable was built for Windows using PyInstaller.

The Omniprogram gave me a an understanding of Python and Tkinter vastly greater than I had before in the process of building user-friendly applications via the Tkinter library.

## [Computer Graphics Spaceship](https://github.com/KesseNones/ComputerGraphicsSpaceship)
A good demonstration of computer graphics using WebGL and JavaScript. 

This project can be run using a Python web server after cloning the repo. When the localhost at port 8000 is connected to via a browser of choice and the `main.html` file is selected, the user can see a 3D spaceship floating over a small landscape made of gray mountains and an ocean of blood. Making this project for my computer graphics class was very rewarding as I saw parts of it come together.

This was the culimation of my entire computer graphics class, fully cementing how 3D graphics work in the first place. This was a fantastic increase to my skills in regards to WebGL and JavaScript.

## [CS 360 (Systems Programming) Final Project](https://github.com/KesseNones/CS360FinalProject)
The final project for my systems programming class in Fall Semester of 2022 at university. 

It's a good demonstration of my experience with C as well as local networking using C's sockets. 

This program also utilizes multi-processing so many clients can connect to one server. 

If you happen to be a WSUV student taking CS 360 looking at my GitHub, don't use this to cheat!

Warning aside, this gave me a huge boost to my abilities with the C programming language.

## [CS 360 Homework Solutions](https://github.com/KesseNones/CS360-HW)
These are all the completed homework assignments that I have from the same class of the final project shown above. They showcase more experience I have with C. 

If you happen to be a WSUV student taking CS 360 looking at my GitHub, don't use these to cheat!

These projects were what really taught me how to write code in C correctly.

## [CS 450 Algorithms Projects Solutions](https://github.com/KesseNones/CS450-Algorithms-Projects)
A compilation of five algorithms projects written in Rust that showcase my experience with some of the classic algorithms as well as using Rust. 

If you're a WSUV student taking CS 450, don't cheat with these!

These projects were helpful in cementing my foundational knoweldge of Rust before I made a programming language in it.

## [Mars Crawler](https://github.com/KesseNones/MarsCrawler)
A PacMan clone that was made for my fall 2023 Game Design class at university, using IntelliJ IDEA and built using Gradle. 

The program itself was made using Java *(shudders)*. 

Jokes aside, it contains three levels of collecting resources in alien caves and running from blobs. 

This project improved my knowledge of Java and how to use it for making games, the one place where OOP actually isn't too bad. Also the second time I had major exposure to the BadLogic Gdx game development API.

## [Breakout Knockoff](https://github.com/KesseNones/KnockOffBreakout)
Implemented for the same fall 2023 Game Design class as a two week homework project that was a recreation of breakout.

This laid the foundation for game design using Java and Gdx.

## [Xtreme Pong](https://github.com/KesseNones/CS-320-Project)
This project was made using Unreal Engine 5 and C++. 

It's called `Xtreme Pong` because it was supposed to be pong that was "Xtreme<sup>TM</sup>", basically Pong but with extra epic features like explosions and fire everywhere with tons of features. As it turned out. It was way harder to do than anticipated.

It was painful and gross but as a group of four over the course of a few months, we implemented a game of Pong that ran at 15 FPS on a halfway decent machine. 

I was in charge of making the scoreboard work, state changes, explosions, and sound effects. The other members did other important parts of the game. One did the ball, one did the paddles and the menu and very early powerups, and one just mooched off our hard work. Group projects, amirite? 

It's doubtful that this hunk of junk still works but if you can clone this repo and get it running using Unreal Engine, I applaud you greatly. 

The mess of this project aside, I learned an immense amount about how Unreal Engine works and how to integrate C++ with it, both of which are very useful skills especially in the realm of game design. I also learned how to manage a Git repo with other people for the first time too.

## Contact Me 💬
- [LinkedIn](https://www.linkedin.com/in/jesseangusjones/)
- [Email](mailto:jesse.angus.jones@gmail.com)
