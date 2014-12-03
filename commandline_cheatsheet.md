Command line basics - cheat sheet
===========
<br>

**`ls`**<br>
list all files and folders contained within the current directory
<br>
**`ls -al`**<br>
same as above, but outputs a neater list (one line per file/folder) and displays additional information
<br><br>
**`mkdir`** `mynewdirectory`<br>
*make dir:* creates a new subdirectory (= directory within the current directory) with the name *mynewdirectory*
<br><br>
**`cd`**<br>
*change directory*<br>if you don't add anything after the cd command, you change to your "home" directory, or main user directory (which usually carries your user name and contains all your personal files)<br>
**`cd`** `mynewdirectory`<br>
enter the directory called *mynewdirectory*, which is contained within the current directory / which sits one level "below" the current directory (note that you can only enter directories which already exist!)<br>
**`cd`** `..`<br>
go back "up" one level, to the directory containing the current directory / the "parent" directory
<br><br>
**`pwd`**<br>
*print working directory*: prints out the full path to the current directory, lets you find out where in your file system you currently are
<br><br>
**`touch`** `somefile.txt`<br>
**`touch`** `anotherfile.txt`<br>
creates the empty text files called *somefile* and *anotherfile* in the current directory, which you can then open and edit in any program that can handle .txt files (e.g. text editors, code editors,...)
<br><br>
**`mv`** `somefile.txt` `newname.txt`<br>
*moves* or renames a file; in this case, the text file *somefile.txt* is renamed to *newname.txt*<br>
**`mv`** `newname.txt` `mynewdirectory/hello.txt`<br>
moves the file *newname.txt* from the current directory to the subdirectory *mynewdirectory* (which must already exist within the current directory!) and renames it to *hello.txt* at the same time
<br><br>
**`cp`** `anotherfile.txt` `copy_of_anotherfile.txt`<br>
creates an exact *copy* of the file *anotherfile.txt* with the name *copy_of_anotherfile.txt*<br>