# Bash Scripting

## Getting started

### Set commit message template

There is a template file implemented for commit messages in order to keep changes tracking as clear as possible.
This template file is configured as follows:

1. In the root directory of the repository run the command `git config --global commit.template ~/.gitmessage.txt`.
2. Now, every time you make a commit just run on the terminal `git commit` and an editor with the message template will show up.
3. When the message is filled, press _Cntl+O_ to save it.
4. Press _Cntl+X_ to close the editor.

### Ignore directory

In order to save usefull files (eg. .txt or .png) but keep them untracked, the `.gitignore` file has a directory called `ignore`.
