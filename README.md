# terminal_alliases_for_git
So you recentlymoved to linux or have sarted developing on linux and<br>
encountered the long git commands which you'd like to shorten, don't worry, why?<br>
Because I gatchu my friend.<br>
In Linux, setting aliases and making them permanent are a little bit easier than windows.<br>

## Aliases in linux
Now in linux there exists multiple types of terminals since as you might have heard,<br>
there are so many distributions out there each with its own or borrowed base.<br>
Don't be scared I'll take your through the most common, the bash terminal<br>

To create a permanent alias, we will need to edit the `~/.bashrc` file. You can open this file with nano or your preferred text editor.<br>
Here I will use vi as text editor example.<br>

```
$ vi ~/.bashrc
```

## Bash Aliases
At the bottom of this file, you can add your permanent aliases.<br>
These are just some examples and you coud create as many as you want.<br>

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
```$ source ~/.bashrc```
