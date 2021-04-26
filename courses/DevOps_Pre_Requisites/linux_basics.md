## Linux Basics

### 1. Basic Commands

`echo` prints to screen. used when you want to print env vars  
`ls` lists files and folders  
`cd` change directories  
`pwd` present working directory  
`mkdir` make directory  
can run multiple commands in one line by separating them with a `;`  
`mkdir -p` create directory hierarchy  
`rm -r` remove directory and contents  
`cp -r` copies content from one directory to another. specify directories after `-r`  
` touch new_file` creates new file  
`cat > stuff` write to file  
` cat new_file` view contents of file  
` mv old_location new_location` move file, same as cut/paste  
` rm file_name` to delete file

### 2. VI Editor

editor used in Linux to modify files

- `vi file name` to open file in VI

2 modes

- command mode, default
  move around using `arrow keys or KHJL`  
   `x` to delete  
   `dd` to delete line  
   `yy` copy  
   `p` paste  
   `ctrl + u, ctrl +d ` to scroll up/down  
   `:` to save changes  
   ` :w` to save `:w filename` as well  
   `:q` to quit  
   `:wq` to save and quit  
  ` /of` to find stuff ex: "of"
  `n` to move cursor to all occurances of found stuff
- insert mode `i` to switch to `esc` to go back to command mode
