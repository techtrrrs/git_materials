Git basics - cheat sheet
===========
<br><br>

Commands to get started with Git
--
<br><br>

Commands to get started with a new project
--

**`git init`**<br>
*initialises* a git repository; needs to happen only once per directory and applies to all of its subdirectories as well
<br><br>

Commands to inspect your work
--

**`git status`**<br>
checks the status of the files in your git repository - you want to use this command often! differentiates between untracked (working directory), staged (staging area, waiting to be committed) and tracked (committed) files
<br><br>
**`git diff`**<br>
lists the *differences* between the last committed and the current versions of your files (if they were edited at all); only works like this before you add your files to your staging area and is especially helpful to figure out what you should write as your commit message
<br>
**`git diff`** `myfile.txt`<br>
lists the differences between the last committed and the current version of the file *myfile.txt* (if it was edited at all)
<br>
**`git diff --cached`**<br>
add the option --cached if you already added your files to the staging area
<br><br>

**`git log`**<br>
prints out a log of all your commits so far
<br><br>


Commands to do something with your files
--
**`git add`**<br>
**`git add`** `myfile.txt`<br>
**`git add`** `.`<br>

**`git commit`**<br>
**`git commit -m`** `"this is where you describe your changes"`<br>
**`git commit `** `myfile.txt` **`-m`** `"this is where you describe your changes"`<br>

<br><br>

