<h1 align="center">Hi there, I'm <a href="https://daniilshat.ru/" target="_blank">Danila</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h1 align="center">Its my Terminal HomeTask</a> 
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=Let's+start" alt="Typing SVG" /></a>

<h1 align="center">Terminal Homework 1</h1>
<p align="center">
  <img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=Let's+start" alt="Typing SVG" />
  </a>
</p>

This is a Terminal Homework 1 for Bash commands. All the commands are written in GitBash.

1. **Check the current directory:**
   Use the `pwd` command to check the current directory.
   ```bash
   $ pwd
   /d
We got a response that /d is our current directory.
Tip: pwd is an abbreviation of "print working directory"
2. **Create a new folder:**
Let's create a folder (directory) with name terminal_hw1 in current directory with mkdir command.
```bash
   $mkdir terminal_hw1
```
3.Create three new folders:
Use the mkdir command to create three new folders named folder_1, folder_2, and folder_3
```bash
$ mkdir folder_1 folder_2 folder_3
```
4.Change to any of these three folders:
Use the cd command to change to one of the three folders. For example, to change to folder_1:
```bash
$ cd folder_1
```
5.Create five files (three .txt, two .json):
Use the touch command to create five empty files with the specified names and extensions.
```bash
$ touch file1.json file2.json notes1.txt notes2.txt notes3.txt
```
6.Create three new subfolders:
Use the mkdir command to create three new subfolders named subfolder_1, subfolder_2, and subfolder_3.
```bash
$ mkdir subfolder_1 subfolder_2 subfolder_3
```
7.Show the list of current folder elements:
Use the ls command to list the contents of the current folder.
```bash
$ ls
file1.json  file2.json  notes1.txt  notes2.txt  notes3.txt  subfolder_1/  subfolder_2/  subfolder_3/
```
8.Open one of the .txt files, write anything in this file, save, and quit:
Use the cat > command to open and edit a text file. Press Ctrl+C to save and quit.
```bash
$ cat > notes1.txt
[Type your text here, then press Ctrl+C to save and quit]
```
9.Go to the directory located one level above:
Use cd .. to go back one level to the parent directory.
```bash
$ cd ..
```
10.Move any two files to any folder:
Use the mv command to move files from one folder to another.
```bash
$ mv folder_1/file1.json folder_1/file2.json folder_2
```
11.Copy any two files to any folder:
Use the cp command to copy files from one folder to another.
```bash
$ cp folder_2/{file1.json,file2.json} folder_3
```
12.Find a file by name:
Use the find command to search for a file in the current directory and its subdirectories.
```bash
$ find . -name notes3.txt
```
13.Show file content in real-time, filtered by a keyword:
Use tail and grep commands to show only the lines containing a specific keyword.
```bash
$ tail -f ./folder_1/notes1.txt | grep "can"
```
14.Show several of the first lines from a text file:
Use the head command to display the first lines of a text file
```bash
$ head ./folder_1/notes1.txt
```
15.Show several of the last lines from a text file:
Use the tail command to display the last lines of a text file.
```bash
$ tail ./folder_1/notes1.txt
```
16.Show content of a large file:
Use the less command to view the content of a large file with navigation options
```bash
$ less large_file.txt
```
17.Show the current date and time:
Use the date command to display the current date and time.
```bash
$ date
```







   
