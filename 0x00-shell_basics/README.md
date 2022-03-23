# 0x00-shell_basics

This directory contains some bash scripts

## script files

1. 0-current_working_directory

    > This is a script that prints the absolute path name of the current working directory
        
2. 1-listit

    > This is a script that displays the contents list of current directory

3. 2-bring_me_home

    > This is a script that changes the working directory to the user's home directory. No shell variables are used

4. 3-listfiles

    > This is a script that displays current directory contents in a long format

5. 4-listmorefiles

    > This is a script that displays current directory contents, including hidden files (starting with .), in a long format

6. 5-listfilesdigitonly

    > This is a script that displays current directory contents in long format, whith user and gropu IDs displayed numerically, and hidden files

7. 6-firstdirectory

    > This is a script that creaes a directory named `my_first_directory` in the `/tmp/` directory

8. 7-movethatfile

    > This is a script that moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`

9. 8-firstdelete

    > This script deletes the file `betty` from `/tmp/my_first_directory`

10. 9-firstdirdeletion

    > This is a script that deletes the directory `my_first_directory` that is in the `/tmp/` directory

11. 10-back

    > This script changes the working directory to the previous one

12. 11-lists

    > This is a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format

13. 12-file_type

    > This script prints the type of the file named `iamafile`
    >
    > The file `iamafile` will be in the `/tmp` directory when the script will be run

14. 13-symbolic_link

    > This is a script that creates a symbolic link to `/bin/ls`, named `__ls__`
    >
    > The symbolic link is created in the current working directory

15. 14-copy_html

    > This script copies all the HTML files (with the extension `.html`) from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

16. 100-lets_move

    > This is a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`

17. 101-clean_emacs

    > This script deletes all files in the current working directory that end with the character `~`

18. 102-tree

    > This is a script that creates the direcoties `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory
    >
    > Only two spaces (and lines) are used in the script

19. 103-commas

    > This script lists all the files and directories of the current directory, separated by commas (`,`)
    >
    > Directory names end with a slash (`/`)
    >
    > Files and directories starting with dot (`.`) are listed
    >
    > The listing is alpha ordered, except for the direcoties `.` and `..` which are listed at the very beginning
    >
    > Only digits and letters are used to sort; digits come first
    >
    > The listing ends with a new line

20. school.mgc

