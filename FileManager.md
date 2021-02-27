# FileManager
*A simple program that allows for the manipulation of files using Java.*

## Available Commands

* `list`    Prints the contents of the given folder. 
```
Enter a desired command:
list
Enter folder's path:
/Users/folderpathway/
file1.txt
file2.txt
file3.txt
```
* `info`    Prints the name, absolute path, relative path, size, created date and last modified date of the given file/folder. 
```
Enter a desired command:
info
Enter desired file/folder's path:
/Users/user1
Name: user1
Absolute path: /Users/user1
Relative path: /Users/user1
Size: 1056
Created: 15. February 2021. 10:44:59
Last Modified: 26. February 2021. 21:43:13
```
* `mkdir`   Creates a new directory. 
```
Enter a desired command:
mkdir
Enter new folder's path:
/Users/user1/new
Created a folder called new
```
* `rename`  Renames a file/folder. 
```
Enter a desired command:
rename
Enter path of file/folder you want to rename:
/Users/user1/new
Enter new name of file/folder:
newer
Rename successful
```
* `move`    Move a file/folder to a new location. 
```
Enter a desired command:
move
Enter path of file/folder you would like to copy/move:
/Users/user1/moveme
Enter destination path:
/Users/user1/subfolder/
Moving is successfully finished.
```
* `copy`    Make a copy of a file/folder. 
```
Enter a desired command:
copy
Enter path of file/folder you would like to copy/move:
/Users/user1/copyme
Enter destination path:
/Users/user1/copiedfile
Copying is successfully finished.
```
* `delete`  Delete a file/folder.
```
Enter a desired command:
delete
Enter path of file/folder you want to delete:
/Users/user1/deleteme
Folder successfully deleted!
```
* `quit`    Exit the file manager.
```
Enter a desired command:
quit
You're exiting File Manager.
```





