## Commands used in this lesson

**Command options :**

* **Long command options:** Preceded by "--", is like a word. Always need "--" in fornt of it so that Linux recognize it as a long option.   
* **Short Option:** Small option is always preceded by small "-".
```sh
>ls --help
```

* <b>Various options to find help regarding a command:</b>
  - help
  - man
  - /usr/share/doc
  
* `less` command is a pager.</br>
* `[]` Square bracket for a command is optional, you may use a command with that option
* `...` One option or mutiple option can be used for that command. Similarly one or more than one file can be used.

If you forget some command option you can make use of `help`. The command you are already fimilar with and want to check specific 
option. Whereas if you don't know about a command and learn about the option and what that command do then you can make use of `man` pages.

### Using `man` pages

* man has different sections and each section deals with specific topics
  * Executable programs or shell commands - USER COMMANDS
  * System calls (functions provided by the kernel)
  * Library calls (functions within program libraries)
  * Special files (usually found in /dev)
  * File formats and conventions eg /etc/passwd - CONFIGURATION FILES
  * Games
  * Miscellaneous  (including  macro  packages  and  conventions), e.g man(7), groff(7) - DIFFERENT TOPICS, Contains background information
  * System administration commands (usually only for root) - SYSADMIN FILES
  * Kernel routines [Non standard]

Seacrhing something in `man` traverse form 1 till section 9 and if it finds something in any of the section it stops there and gives 
back the result.
