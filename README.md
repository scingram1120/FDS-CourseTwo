# FDS-CourseTwo
##Creating new repo for new class
###Making new changes 
TERMINAL TIPS
Pwd - shows current location
Ls - shows the list of files and directories
Ls - F - shows which files are folders 
Cd / - top level
Cd - allows you to change directories 
Which _file_ - finds the path directory
Cd .. - move up 
Cd ~ - return to home directory
Touch - create a file
Mkdir - create empty directory
Mv -v move file - mv ~/location/file ~/new/location/file/
Rename mv -v old name newname
Rm -v delete file rm -vrf FDS-CourseOne 
Touch __file_ - creates new file
Nano __file_ - opens files in editor, ctrl o, ctrl x,
Go to finder, show path in view, open in terminal, replaces CD
Git fetch - fetches local changes
git log --oneline origin - tells you what was changed 

_____How to move to a file ____
Move to a file
Cd fileyoutomove to



____How to copy a file _____
Copy 
Cp -v fileyouwanttocopy (tab to complete) space whereyouwantittogo


___Tutorial workflow____
Sync pull FDS
Cd ~
Cd git
Git pull in FDS course one
Cp -v ../PythonTutorials
Cd PythonTutorials
Git status
Git add tutorial 
Git commit -am “message”
Git push
Do tutorial
Git commit -am “finished”
Paste url and upload pdf



_____General GIT tips______
start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects
