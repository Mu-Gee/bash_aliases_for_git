# terminal_alliases_for_git
So you recentlymoved to linux or have sarted developing on linux and
encountered the long git commands which you'd like to shorten, don't worry, why?
Because I gatchu my friend.
In Linux, setting aliases and making them permanent are a little bit easier than windows.

## Aliases in linux
Now in linux there exists multiple types of terminals since as you might have heard there are so many distributions out there each with its own or borrowed base
Don't be scared I'll take your through the most common, the bash terminal

To create a permanent alias, we will need to edit the ~/.bashrc file. You can open this file with nano or your preferred text editor. <br>

`$ vi ~/.bashrc`

## Bash Aliases
At the bottom of this file, you can add your permanent aliases.
These are just some examples and you coud create as many as you want.

```
#>>> git aliases >>>
alias init='git init'
alias clone='git clone'
alias fetch='git fetch'
alias merge='git merge'
alias push='git push'
alias pull='git pull'
alias add='git add'
alias commit='git commit -m'
alias checkout='git checkout'
alias branch='git branch'
alias diff='git diff'
alias show='git show'
alias status='git status'
#<<< git aliases <<<
```
After saving your changes and exiting the file, execute the following command to make the changes take effect:
$ source ~/.bashrc
