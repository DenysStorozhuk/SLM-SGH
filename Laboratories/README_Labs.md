# SLM Spring 2022/23 laboratories

##### This repository contains all the information related to the laboratories presented by Professor Łukasz Kraiński. 

**Required software**

During the course we'll use Jupyter Notebook with Julia. 
To run the code provided during classes (laboratories) you'll need:
* [Julia](https://julialang.org/downloads/)
* [Jupyter](https://jupyter.org/install) Notebook or Jupyter Lab
* [Git](https://git-scm.com/)

---
### Issues and answers

If you encounter issues starting Julia from the terminal on a Mac and receive error messages like 
"zsh: command not found: julia" or "ERROR: UndefVarError: julia not defined," 
even though you have installed Julia correctly, you can try the following solution:

1. Open a terminal window.

2. Run the following command in the terminal:


```
sudo ln -s /Applications/Julia-X.Y.app/Contents/Resources/julia/bin/julia /usr/local/bin/julia
```

3. Replace "X.Y" with the version number of your Julia installation. 
For example, if you have Julia version 1.6 installed, the command would be:


```
sudo ln -s /Applications/Julia-1.6.app/Contents/Resources/julia/bin/julia /usr/local/bin/julia
```
Enter your administrator password when prompted. 
Note that when entering your password, the characters won't be visible in the terminal.

After running the command, try starting Julia again by typing julia in the terminal. 
It should now be recognized as a valid command, and the Julia REPL should start without any errors.

#### Explaining the code
By creating a symbolic link using the ln -s command, you are linking the Julia binary file to a directory in your system's PATH variable, making it accessible from any location in the terminal. This allows you to start Julia using the julia command directly without specifying the full path to the Julia executable.
#### Short conclusion
This solution can help resolve the "zsh: command not found: julia" or "ERROR: UndefVarError: julia not defined" 
issues when starting Julia from the terminal on a Mac.
