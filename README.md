🐚 MY-SHELL (Custom UNIX Shell)
C Language | UNIX System Programming | Shell Implementation

A feature-rich custom shell supporting pipelines, redirection,
environment variables, and built-in commands.

## 🚀 KEY FEATURES
✔ Command execution with argument parsing                                                      
✔ Environment variable support (VAR=value)                                          
✔ I/O redirection (<, >, >>)                                                                  
✔ Multi-command pipelines (cmd1 | cmd2)                       
✔ Built-in cd command                                              
✔ Robust error handling                                                                                      

## 🛠️ INSTALLATION & USAGE
1. Clone and build
$ git clone https://github.com/yourname/my-shell.git
$ cd my-shell
$ make

2. Run shell
$ ./myshell
My shell>> ls -l | grep ".txt"

## 💡 EXAMPLE COMMANDS
1. Set variable and use in command
My shell>> MYDIR=/home/user
My shell>> ls $MYDIR

2. Redirect output
My shell>> echo "Hello" > greeting.txt

3. Pipeline example
My shell>> cat file.txt | sort | uniq -c

4. Change directory
My shell>> cd /var/log

## 📂 CODE ARCHITECTURE
my-shell/                           
├── Makefile           # Build automation                                                                                    
├── main.c             # Core shell loop                                                                   
├── my_shell.c         # Command implementations                                                
├── my_shell.h         # Header definitions                                               
└── README             # This document                                                                    

## ⚠️ SYSTEM REQUIREMENTS
✔ Linux/Unix environment                       
✔ GCC compiler                              
✔ GNU Make                              
