# Learn to Code

Welcome to my code learning repository! This repository is a collection of my notes and code snippets as I embark on the journey of learning many different programming languages. 🚀


## Languages

- `C` 
- `Shell Script` 
- `JavaScript` 
- `Python`


I will be using Ubuntu through WSL.  

## Usage

### Learn C
Located in the `c` directory. Made for someone who has never seen C before but also delve into more advanced systems programming topics such as pipes, processes, and sockets. 

`notes.c` contains all the notes I have made along with C code examples. Each different topic is sectioned off into its own function. Similiar to a table of contents, you can view the list of topics in `main()` and ctrl-click them to jump to a topic. These notes are made to be compiled and read on Linux as I made them through Ubuntu on WSL. You can do otherwise but you may get intellisense errors.

If you would like to run code inside a particular topic, simply make that topic be the only function called in `main()`, then compile `notes.c`. You will need a C compiler, for example I use `gcc`. So in shell I will `cd` to the directory containing `notes.c` and run the following command:

```
gcc -o notes notes.c
./notes
```

---
### Learn Shell Script
Located in the `shell-script` directory. Made for someone who has never seen Shell Script before. 

`notes.sh` only contains notes and is not intended to be ran as a script. Rather, users may read through `notes.sh` and test commands in a bash terminal or create their own script in `myscript.sh`. To execute `myscript.sh` from shell, cd to the directory containing my script.sh and run the following command:
```
chmod a+x myscript.sh
./myscript.sh
```

---
### Learn Python
Located in the `python` directory. Made for someone who is already familiar with Python and interested in learning tools for data analysis.

`data_analysis.py` contains detailed notes on using various libraries such as NumPy, Pandas, and Matplotlib. There aren't any notes for learning Python from the ground up for this section unlike the others.

---

Happy coding.
