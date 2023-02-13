# Lab Report 3
**Researching Commands**

[More grep command option](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)

## *grep* Command

### Search files recursively from subdirectories, starting from the current directory
Using `-r` option in grep can search files recursively from subdirectories, starting from the current directory
![Image](screenshots/lab3_sc/sc-r.jpg)
You can either put the command option `-r` in the front or in the end
![Image](screenshots/lab3_sc/sc-r2.jpg)

### Prints only a count of the lines that match a pattern
Using `-c` option in grep can print only a count of the lines that match a pattern
![Image](screenshots/lab3_sc/sc-c.jpg)
You can also use with other command option like `-r`. This can be useful, 
for example, you can search how many lines contains the string "Hong Kong" in every file in the current directory 
![Image](screenshots/lab3_sc/sc-c2.jpg)

### Display the matched lines, but do not display the filenames.
Using `-h` option in grep can display the matched lines, but do not display the filenames
![Image](screenshots/lab3_sc/sc-h.jpg)
Another example of using `h`
![Image](screenshots/lab3_sc/sc-h2.jpg)

### Displays list of a filenames only.
Using `-l` option in grep can display list of a filenames only.
![Image](screenshots/lab3_sc/sc-l.jpg)
It could be really useful when only looking for the file for a more clear display in the terminal
![Image](screenshots/lab3_sc/sc-l2.jpg)

