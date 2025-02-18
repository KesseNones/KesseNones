# 👋 Greetings! 
# 📚 About 

I am Jesse, a computer science degree holder looking to contribute to the world and find an eventual career in *something*. I enjoy programming languages and systems programming concepts but have also dabbled in most other fields of computer science in my education, excepting maybe machine learning stuff but I could learn that too. Overall, I specialize in programming language design at present before having made a career. When not coding, I play video games and both write and learn about sci-fi lore.
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

The compiler takes a `.lmao` file, parses it, turns it into an abstract syntax tree,  translates the ast into a Rust file, then lastly uses rustc to compile it to machine code. This results in a language marginally faster than Python when compiled!
## [EcksDee Programming Language](https://github.com/KesseNones/EcksDee-Programming-Language)
The predecessor to Lmao that uses Haskell for both interpretation and compilation of `.xd` files. 

The interpreter works just like Lmao but with Haskell and less optimization. The compiler works the same as with Lmao just with Haskell and ghc instead of the Rust equivalents.

It's not updated much these days but it's a cool step in the journey and shows off some good skill in translating functional programming to imperative via interpretation. 

While it may not be as good as Lmao, it's the first language made by me and it therefore has a special place in my core.

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

Overall, this isn't a huge project or anything but is a good showcase of my abilities to work with Docker to an extent and use HTTP requests to do basic backend endpoints. 

## [Omniprogram Side Projects](https://github.com/KesseNones/Omniprogram-Side-Projects)
An old repo containing more than 100 GUI Python programs that are all linked together through janky main calls. This effectively results in a large program that can do many things including conversions, clock displays, and calendars. 

This repo is also rarely updated with the exception of the occasional fix but it's still a fun set of GUI programs. Windows users can also run this without Python since an executable was built for Windows using PyInstaller.
## [Computer Graphics Spaceship](https://github.com/KesseNones/ComputerGraphicsSpaceship)
A good demonstration of computer graphics using WebGL and JavaScript. This project can be run using a Python web server after cloning the repo. When the localhost at port 8000 is connected to via a browser of choice, the user can see a 3D spaceship floating over a small landscape made of gray mountains and an ocean of blood. Making this project for my computer graphics class was very rewarding as I saw parts of it come together.
## [CS 360 (Systems Programming) Final Project](https://github.com/KesseNones/CS360FinalProject)
The final project for my systems programming class in Fall Semester of 2022 at university. It's a good demonstration of my experience with C as well as local networking using C's sockets. This program also utilizes multi-processing so many clients can connect to one server. If you happen to be a WSUV student taking CS 360 looking at my GitHub, don't use these to cheat!
## [CS 360 Homework Solutions](https://github.com/KesseNones/CS360-HW)
These are all the completed homework assignments that I have from the same class of the final project shown above. They showcase more experience I have with C. If you happen to be a WSUV student taking CS 360 looking at my GitHub, don't use these to cheat!
## [CS 450 Algorithms Projects Solutions](https://github.com/KesseNones/CS450-Algorithms-Projects)
A compilation of five algorithms projects written in Rust that showcase my experience with some of the classic algorithms as well as using Rust. If you're a WSUV student taking CS 450, don't cheat with these!
## [Mars Crawler](https://github.com/KesseNones/MarsCrawler)
A crummy PacMan clone that was made for my fall 2023 Game Design class at university, using IntelliJ IDEA and built using Gradle. The program itself was made using Java *(shudders)*. Jokes aside, it's okay. The movement is janky but it works. It contains three levels of collecting resources in alien caves and running from blobs. Eventually I may come back to this to make it less terrible.
## [Breakout Knockoff](https://github.com/KesseNones/KnockOffBreakout)
Implemented for the same fall 2023 Game Design class as a two week homework project that was a recreation of breakout. It's janky and the collisions are gross but it works well enough.
## [Xtreme Pong](https://github.com/KesseNones/CS-320-Project)
This project was made using Unreal Engine 5 and C++. It was painful and gross but as a group of four over the course of a few months, we implemented a game of Pong that ran at 15 FPS. I was in charge of making the scoreboard work, state changes, explosions, and sound effects. The other members did other important parts of the game. One did the ball, one did the paddles and the menu, and one just mooched on our hard work. Group projects, amirite? 

It's doubtful that this hunk of junk still works but if you can clone this repo and get it running using Unreal Engine, I applaud you greatly. 
## Contact Me 💬
- [LinkedIn](https://www.linkedin.com/in/jesseangusjones/)
- [Email](mailto:jesse.angus.jones@gmail.com)
