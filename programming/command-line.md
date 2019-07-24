# Command Line

## Snippets

Make sounds in Mac terminal

```bash
afplay /System/Library/Sounds/Funk.aiff
say "Focus is starting"
```

Create a symbolic link in Terminal \([source](https://apple.stackexchange.com/a/115647/50815)\):

```bash
ln -s /path/to/original /path/to/symlink
```

Open long output for easier reading \(`q` to exit; [source](https://superuser.com/a/1159908/102414)\):

```bash
my_command | less
```

Filter for lines matching \([source](https://stackoverflow.com/a/9074384/937377)\):

```bash
my_command | grep search_term
```

Show a notification in Mac Terminal:

```bash
osascript -e 'display notification "Get to work!" with title "Focusing"'
```

## Links

[Column 80](https://stackapps.com/questions/542/column-80-plain-text-optimised-stack-exchange) - StackExchange network optimized for text-only browsers

[Ctrl+L in terminal](https://askubuntu.com/questions/434240/ctrll-in-terminal) \#article - “ctrl + L just clear the terminal screen.”

[Docopt](http://docopt.org/) - “Command-line interface description language”

[How can I increase the cursor speed in terminal?](https://stackoverflow.com/a/4490124/937377) \#article - I found that the standard preferences panel gave me plenty of speed, but it's neat to know you can do this.

> Everybody knows that you can get a pretty fast keyboard repeat rate by changing a slider on the Keyboard tab of the Keyboard & Mouse System Preferences panel. But you can make it even faster! In Terminal, run this command:
>
> `defaults write NSGlobalDomain KeyRepeat -int 0`
>
> Then log out and log in again. The fastest setting obtainable via System Preferences is 2 \(lower numbers are faster\), so you may also want to try a value of 1 if 0 seems too fast. You can always visit the Keyboard & Mouse System Preferences panel to undo your changes.
>
> You may find that a few applications don't handle extremely fast keyboard input very well, but most will do just fine with it.”

[How can I tell if a directory from “ls” is a symlink?](https://stackoverflow.com/a/15103946/937377) \#article - “Use ls -l”

[Mac OS X: Set / Change $PATH Variable](https://www.cyberciti.biz/faq/appleosx-bash-unix-change-set-path-environment-variable/) \#article - “$PATH is nothing but an environment variable on Linux, OS X, Unix-like operating systems, and Microsoft Windows. You can specify a set of directories where executable programs are located using $PATH. The $PATH variable is specified as a list of directory names separated by colon \(:\) characters.”

[Victory CLI](https://formidable.com/blog/2016/08/29/terminal-charts-with-victory-cli/) - terminal graphing library



