# SnakeGame
## webiste to run the program:
- https://joshua-cheng2210.github.io/SnakeGame/

## How to run the program:
```bash
1) find a terminal and enter the following commands
2) git clone https://github.com/joshua-cheng2210/SnakeGame.git
3) npm install
3) npm run dev
```

## language skills developed:
- javascript
- CSS
- HTML
- and other configuration settings like 
    - .yml (for deploying on git hub), 
    - packge.json (for initializing and maintaining your program's dependencies)

## Packages uesd:
- vite (to run your program while in development to catch bugs in early stages of dev build)
- javascript-obfuscator (to bundle and compile everything together so that it can be hosted on git hub actions)
- Git Hub Actions

## Topics learnt
- how does Javascript (vanilla), CSS and HTML all work together to build an interactive webste
- how to initilize npm project
- how to host to program on git hub actions
- learnt about project depedencies and dev dependencies

## Mistakes made that got me debugging 24 hours
- in my index.html, i put "/src/something.js" instead of "./src/main.js" (./ makes a big different than /)
- in your vite.config.js, make sure to add a line base: './', // Ensure the base path is set correctly for GitHub Pages
- dyk, wou can also kinda debug a little through google. (press F12)
- jekyll is adecent yml file that u can use to deploy your program through git hub (don't need to take it from previous project)