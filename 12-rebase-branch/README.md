# Git Kata: rebase branch
## Setup:
In your terminal, run
```
$ ./setup.sh && cd exercise
```


## The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.

1. Which branches exist?
1. Look at the log for the master branch
1. Check out the uppercase branch
1. How does the log compare to the log on the master branch?
1. Rebase your uppercase branch with the master (`git rebase master`)
1. What did just happen? Draw it!
1. Now checkout the master branch
1. Merge uppercase into master
1. What does the log look like now?

Au lieu d'utiliser un rebasage suivi d'une avance rapide, utiliser la commande `cherry-pick` pour arriver au même résultat.
Un diff entre les deux derniers *commits* prouvera qu'ils sont identiques.

## Useful commands
- `git checkout <branch-name>`
- `git rebase <branch-name>`
- `git log --oneline --decorate --graph --all`
- `git merge <branch-name>`
