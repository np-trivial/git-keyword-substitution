# git-keyword-substitution
SVN-style keyword substitution brought to Git

Inspired by the question and answer [here](http://stackoverflow.com/a/11535358), I created my own version that did not require perl or awk, or storing any scripts on the file system. It's all stored in the git config files. Also, it works for the `Date`, `Revision`, and `Author` keywords.

Currently, installation is rudimetary. 

1. Append (or create) the gitattributes file here to .gitattribute file at the root of your Git project
1. Append (or create) the git/config file here to the .git/config file at the root of your Git project

TODO: create an installation script
