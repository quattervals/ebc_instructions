 
// check out a new branch to add code
git branch add_to_principles
git switch add_to_principles
//add one line

// see what you have changed compared to HEAD
git diff

// add your changes (selectively)
git add -p
// see your to-be-commited changes
git diff --cached

// commit your change
git commit

// add another line, and commit it

// check the log
git log --graph --oneline --all --decorate

// this is hard to memorize --> add shortcut in ~/.gitconfig (no need to reload terminal)

```bash
[alias]
    plog = log --graph --oneline --all --decorate
```


