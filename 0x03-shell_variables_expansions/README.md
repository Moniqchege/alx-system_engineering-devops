Shell, init files, variables and expansions

Shell
A shell is a command-line interface for interacting with an OS. Popular Unix-like shells include Bash, Zsh, and Fish.

Init Files
Init files are scripts executed at the start of a shell session. They configure the shell's behavior, set variables, and define aliases/functions. Common locations:

Bash: ~/.bashrc, ~/.bash_profile
Zsh: ~/.zshrc
Fish: ~/.config/fish/config.fish
Init files customize the shell environment.

Variables
Variables store and manipulate data in a shell. Types:

Environment Variables: Global variables like PATH, HOME.
Shell Variables: Local to the session

Expansions
Expansions manipulate variables/commands:

Variable Expansion: $VARIABLE_NAME
Command Substitution: `command` or $(command)
Wildcards: *, ? for file globbing.
Tilde Expansion: ~ represents the home directory.
