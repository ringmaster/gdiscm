Instructor
: Owen Winkler

What is SCM (Source Code Management)? 
aka - "Version Control" or "Revision Control"

[Owen's blog post on version control](http://redalt.com/5-reasons-you-should-be-using-version-control "5 Reasons You Should Be Using Version Control")

# Vocabulary

working copy
: code on which you are currently working
production
: code that is out there for the world to see and use
repository ("repo")
: official copy of your code (revisions, history, etc.)  
stage
: designate as ready to be comitted to the repository
: mark as waiting to be committed
commit
: put on the repo
revert
: go back a version
head
: most recent version of the branch in the repo
branch
: new avenue of code development
master
: main branch
tag
: name of a specific commit
remote
: a repository that is not on the local machine
pull
: get code from a remote repo
push
: send code to a remote repo
merge
: integrate changes made by more than one developer
conflict
: what happens when code cannot be merged because it's been changed by more than one developer at the same time
resolve
: go through the process of handling conflicts
hash
: hexadecimal string of characters that labels a commit in the repo

Next we went over basic shell commands.

Files can have (in general) four states: 
- Untracked (git doesn't know about it)
- Tracked (git knows about it)
- Changed (git knows about it and a change has been made)
- Staged (git knows about it and it is ready to be committed)

rebase
: git command that allows you to combine a bunch of commits into one larger commit

Rebase is a *powerful* command, so use it with **caution**!

This [online book](http://git-scm.com/book "Pro Git") is a good git resource.

Don't forget to fill out the [course evaluation](ph.ly/gdi-scm "Source Control Management Feedback")!