# linuxinterestingfacts

## check out the file permission of linux command sudo
```bash
ls -l $(which sudo)
```

## check out the file permission of linux command su 
```bash
ls -l $(which su)
```

## .bashrc vs .bash_profile vs /etc/bashrc vs /etc/bash_profile
Interactive shell load commands from .bash_profile
Non-interactive shell (subshell) loads commands from .bashrc
[Link for more details on bashrc and bash_profile](https://phoenixnap.com/kb/bashrc-vs-bash-profile)
