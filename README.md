# bash_PS1
bash PS1 configurations

## Bash Generator website
https://www.kirsle.net/wizards/ps1.html

## Examples

### Example1
export PS1="\[\e[1;31m\]\[┌─\][\[\e[1;33m\]\u\[\e[1;32m\]@\[\e[1;34m\]\h\[\e[1;31m\]]\n\[\e[1;31m\]\[└─\][\[\e[1;35m\]\W\[\e[1;31m\]]\[\e[1;36m\]\$ \[\033[0m\]"

![alt text](https://github.com/tag2000sa/bash_PS1/blob/master/Screenshot%20at%202017-10-13%2023-20-17.png)

=================================================================================================================

### Example2
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

=================================================================================================================

### Example3
#### Text Colors
black_txt='\[\e[30m\]'
red_txt='\[\e[31m\]'
green_txt='\[\e[32m\]'
yellow_txt='\[\e[33m\]'
blue_txt='\[\e[34m\]'
magenta_txt='\[\e[35m\]'
cyan_txt='\[\e[36m\]'
light_gray_txt='\[\e[37m\]'
default_txt='\[\e[39m\]'
gray_txt='\[\e[90m\]'
light_red_txt='\[\e[91m\]'
light_green_txt='\[\e[92m\]'
light_yellow_txt='\[\e[93m\]'
light_blue_txt='\[\e[94m\]'
light_magenta_txt='\[\e[95m\]'
light_cyan_txt='\[\e[96m\]'
white_txt='\[\e[97m\]'

#### Background Colors
red_bg='\[\e[41m\]'
green_bg='\[\e[42m\]'
yellow_bg='\[\e[43m\]'
blue_bg='\[\e[44m\]'
magenta_bg='\[\e[45m\]'
cyan_bg='\[\e[46m\]'
light_gray_bg='\[\e[47m\]'
default_bg='\[\e[49m\]'
light_red_bg='\[\e[101m\]'
light_green_bg='\[\e[102m\]'
light_yellow_bg='\[\e[103m\]'
light_blue_bg='\[\e[104m\]'
light_magenta_bg='\[\e[105m\]'
light_cyan_bg='\[\e[106m\]'
light_gray_bg='\[\e[107m\]'

#### Text Format
bold_txt='\[\e[1m\]'
format_off='\[\e[0m\]'

PS1="${red_txt}╭─❪${light_green_txt}\u${blue_txt}${bold_txt} \$${format_off}${red_txt}❫\n├─❪${yellow_txt}${light_magenta_txt}\w${format_off}${red_txt}❫\n├─⚫ ${yellow_txt}\@${format_off}${red_txt}\n⚫ ${format_off}${green_txt}"
![alt text](https://github.com/tag2000sa/bash_PS1/blob/master/screen.png)

=================================================================================================================

### Example4
#### Text Format

export PS1="\\[\e[1;31m\\][\\[\e[1;33m\\]\u\\[\e[1;32m\\]@\\[\e[1;34m\\]\h\\[\e[1;31m\\]]\n\\[\e[1;31m\\][\\[\e[1;35m\\]\W\\[\e[1;31m\\]]\\[\e[1;36m\\]\$ \\[\033[0m\\]"

![alt text](https://github.com/tag2000sa/bash_PS1/blob/master/ex4.png)

=================================================================================================================

### Example5
#### Text Format

export PS1='\n\[$(tput bold)\]\[$(tput setaf 6)\]\t\[$(tput setaf 1)\][\[$(tput setaf 3)\]\u\[$(tput setaf 7)\]@\[$(tput setaf 2)\]\h \[$(tput setaf 6)\]\W\[$(tput setaf 1)\]]\[$(tput setaf 5)\]\\$ \[$(tput sgr0)\]'

![alt text](https://github.com/tag2000sa/bash_PS1/blob/master/Screenshot_20200218_160428.png)

=================================================================================================================
