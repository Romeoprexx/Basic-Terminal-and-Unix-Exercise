# Basic-Terminal-and-Unix-Exercise

Part I

make a directory called first PS C:\Users\PC\desktop> mkdir first

change directory to the first folder PS C:\Users\PC\desktop> cd first

create a file called person.txt PS C:\Users\PC\desktop\first> ni person.txt

change the name of the file to another.txt PS C:\Users\PC\desktop\first> ren person.txt another.txt

make a copy of the another.txt file and call it copy.txt PS C:\Users\PC\desktop\first> cp another.txt copy.txt

remove the copy.txt file PS C:\Users\PC\desktop\first> rm copy.txt 

make a copy of the first folder and call it second PS C:\Users\PC\desktop> cp -r first second

delete the second folder PS C:\Users\PC\desktop> rmdir second


Part II

What does the man command do? Type in man rm. How do you scroll and get out? The man command lists the manual for a command -  it is equivalent to help in windows C:\> HELP | find /i "ACL"

Look at the man page for ls. What does the -l flag do? What does the -a flag -do? The -l flag lists files in a list format with more detail and the -a lists all files and folders including hidden ones

Type the following command to download and save the contents of google.com: C:\curl https://www.google.com > google.html C:\curl https://www.google.com > google.html

Use less to look at the contents of google.html. the closest equivalent to the less command in windows is more. therefore, google.html| more

Look at the man page for less. Read the section on /pattern. Search for the text hplogo in the google.html file. less -p hplogo google.html

How do you jump between words in the terminal? left/right arrow keys

How do you get to the end of a line in terminal? Ctrl + E

How do you move your cursor to the beginning in terminal? control + a How do you delete a word (without pressing backspace multiple times) in -terminal? option + delete

What is the difference between a terminal and shell? The terminal is an application that gives us command line interfaceto the computer. The shell is what actually handles commands

What is an absolute path? An absolute path is a path that starts from the root route and gives the complete location for a file or folder. it usually start with /

What is an relative path? A relative path is a path that starts at the current location and not the root route. usually start with ~

What is a flag? Give three examples of flags you have used. A flag adds additional functionality to an existing command, i have used the -l for the ls command and -r for the cp and rm commands

What do the r and f flags do with the rm command? r will remove folders and recursively go through each folder and file and f will force removal
