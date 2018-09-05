# Git Kata: Configuring git


## 1. Git Initial Configuration
1. `git config user.name "John Doe"`
2. `git config user.email "johndoe@example.com`

For the windows peeps:
- `git config --global core.editor notepad`

## Aliases

You can set up aliases as such:
* `git config --global alias.lol 'log --oneline --decorate --graph --all'`

This might be useful to you.

## 2. Downloading and Installing on Windows

* Download at [https://git-scm.com/download/win](https://git-scm.com/download/win)
* Install using the pre-selected defaults
* Create a key for authenticating against ssh-enabled repositories:
https://help.github.com/articles/generating-an-ssh-key
* or...
* open the Git Bash client you just installed and type:

`ssh-keygen -t rsa -b 4096 -C "your_email@somewhere.com"`

This generates public/private keys in %USERPROFILE%/.ssh (named id_rsa.pub)
