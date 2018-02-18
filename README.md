# bash_PS1
bash PS1 configurations

## Bash Generator website
https://www.kirsle.net/wizards/ps1.html

## examples

export PS1="\[\e[1;31m\]\[┌─\][\[\e[1;33m\]\u\[\e[1;32m\]@\[\e[1;34m\]\h\[\e[1;31m\]]\n\[\e[1;31m\]\[└─\][\[\e[1;35m\]\W\[\e[1;31m\]]\[\e[1;36m\]\$ \[\033[0m\]"

![alt text](https://github.com/tag2000sa/bash_PS1/blob/master/Screenshot%20at%202017-10-13%2023-20-17.png)



red='\[\e[1;31m\]'
green='\[\e[1;32m\]'
yellow='\[\e[1;33m\]'
blue='\[\e[1;34m\]'
pink='\[\e[1;35m\]'
aqua='\[\e[1;36m\]'
white='\[\e[1;97m\]'
format_off='\[\e[0;0m\]'
PS1="${red}┌[${yellow}\u${green}@${blue}\h${red}]\n└[${pink}\W${red}] ${aqua}\$${white} -> $format_off"

![alt text](https://github.com/tag2000sa/bash_PS1/blob/master/Screenshot_20180218_104118.png)
