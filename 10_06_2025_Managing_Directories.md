# Managing Directories / Folders

### To open terminal
    ctrl + Alt + t  ->  terminal

*   Each directory can contain few more files or sub directories.

*   Change to another directory
        $cd directory_name

*   Go back to previous directory
        $cd ..

*   "Tab" can be used to fill remain characters after first character of directory or file name.

*   Using a single command to jump to 4th sub directory
        $cd Desktop/C/Arrays/Programs

*   Single command to move back multiple directories
    - If we use $cd it will move back to main or home directory
    - root/home/viven   -> viven is home directory

*   $pwd    ->  Present/current working directory

*   $cd /   -> root directory will be taken

*   Having seperate workspace have seperate directories for multiple users

*   Creates new directory
```
    $mkdir < directory_name >
```
    -   For documentation use - $man mkdir <br>
                              - $mkdir --help

*   Remove a file
```
    $rm <file_name>
```

### Remove Directory
1)  Empty Directory
    -   $rmdir  < directory_name >
    -   $rm -d dir_name
    -   -d -> flags/options

2)  Non-Empty Directory
    -   $rmdir cannot be used to remove non-empty directory
    -   $rm -d dir_name     -> Won't work
    -   $rm -r dir_name
        -   recursively go to every sub directory and remove files.