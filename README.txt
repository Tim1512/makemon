# makemon by Yokai Seishinkage #

Make a single (or many) monitor mode wireless interfaces with unique mac addresses. Makemon is a slim tool for creating a
single or many virtual monitor-mode wireless interfaces for various wireless tasks. You can use command-line options or you
can use the simple command-line user interface to select what options you want to use. There is no limit on how many interfaces
you can choose to create but, more than 100 will take some time to create or remove.

# Dependencies
1.) iw

# Installation
Open linux terminal and enter each step in order.

1.) git clone https://github.com/Yo-kai-Sei-shin-kage/makemon.git
2.) cd makemon/
3.) cp makemon_v1.2-18 /usr/bin/makemon
4.) chown $USER:$USER /usr/bin/makemon
5.) chmod u+x /usr/bin/makemon

# Usage

[USER INTERFACE USAGE]

   Run <makemon> as a command and follow the prompts.

[COMMAND-LINE USAGE]

   makemon [-olrh] [2..99+]

[OPTIONS]

  -o       Create a single virtual monitor interface.
  -m       Create multiple virtual monitor mode interfaces.
  -l       Show created virtual monitor mode interfaces.
  -r       Delete all virtual monitor interfaces.
  -h       Show this menu.
 
# Disclaimer
This tool is released to the public in the hopes that it will be useful. This has not been coded in the most perfect
and absolutely best manner. You will notice there is little to no comments. This is done intentionally to spur users into
looking into bash programming on their own and learning the shell more effectively through self-study.
Learn to help improve open source tools and the open source community and we can all benefit.

# Bugs/Issues
Please report any bugs, issues, and requests for features here: https://github.com/Yo-kai-Sei-shin-kage/makemon/issues

Cheers!!
