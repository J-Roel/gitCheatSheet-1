## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` -  Show commit logs

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index/stage

`$ git add -A` - automatically stage all tracked, modified files before the commit

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - to create a new branch

#### Merging

`$ git merge <branch name>` - put branch changes together in master
