#LINUX MANUAL

> A kerner is a program that allocates and controls hardware resources in a system. 
    A kernel act as an interface between your raw hardware (RAM, processor, storage) and the Operating System.

> A linux is a kernel upon which you can build an Operating System (also called Linux Distros, say for example: Ubuntu, Alpine, Fedora).
    Linux Distribution use the Linux Kernel together with the GNU Operating System.

---------------------------

Basic Linux Commands

--------------------------

1. ls:  To list directories
   
    a. ls -a : To list all directories including hidden ones
   
    b. ls -l : More details about each of the directories
   
    c. ls -la: More details about each of the directories including hidden ones

2. pwd: Print working directories

3. cd: To navigate through directories
   
    a. cd .. : to go back one directory
   
    b. cd - : to go back to the last directory you were on

6. mkdir: To make directories in linux

7. mv: Move or rename file in linux
   
    example: mv {source_file_name} {target_destination}
   
    example: mv {current_file_name} {new_file_name}

9. cp:  Coping files in linux
    
    example: cp {source_file_name} {destination_with_file_name} 

11. rm: Delete files or directories
    
    a. rm {file_name} ; to delete a single file
    
    b. rm -rf {directory_name} : remove recursively by force to delete a folder

13. touch: Create blank/empty files

14. ln: Create symbolic links (shortcuts) to other files
    
    example: ln -s {source_file_name} {destination_with_file_name} 

16. cat: Display file contents on the terminal
17. clear: Clear the terminal display
18. echo: Print any text that follows the command
19. man: Access manual pages for all linux commands

20. uname: To get the basic information about the OS
    a. uname -mrs : to get more information about the OS (OS name, kernel version, processor type)
    b. uname -a : to get extra more information about the OS 

21. whoami: Get the active Username

22. tar: To extract and compress files in linux
    example to create a tar folder: tar -cvf {destination_folder_name} {source folder name}
    example to extarct a tar folder: tax -xvf {folder_name}

23. grep: Search for a string within an output
    example: cat {file_name} | grep {output_string}
    example: cat {file_name} | grep {output_string} -n
    example: ps | grep {output_string}

24. head: Return the specific number of lines from the top
    example: head {file_name}
    example: head -n 5 {filename} <- Returns first 5 lines

25. tail: return the specific number of lines from the bottom

26. printenv : to print all the environment variables
27. export: Export environment vaiables in linux (only for that particular runtime)
    exmaple: export name={name_which_you_want_to_give}

28. zip: Zip files in linux
29. unzip: Unzip files in linux
30. ssh: Secure shell command in linux

31. service: To start and stop services (services are collection of task)
    a. service --status-all : to get all the services

32. ufw: Firewall command

33. ps: Display active processes (processes are task)
    a. ps aux : all the running tasks

34. kill and killall: Kill active processes by process ID or name

35. df: Display disk filesystem information
    a. df -h

36. chmod: Command to chnage file permission (r = read, w = write, x = executable)
    example: chmod +x {application_name} <- making application executable
    example: chmod 777 {application_name} <- giving application all possible permissions (not recommended)

37. ifconfig: Display network interfaces and IP addresses
38. curl: to send http request and fetch data from it
39. wget: Direct download files from the internet

40. sudo: Command to escalate privilegs in Linux
41. apt, pacman, yum, rpm - Package manager depending on the distro
    snap - Ubuntu package manager
    example: sudo apt install {application_name}
    example: sudo apt remove {application_name}
    example: sudo apt update
    example: sudo apt upgrade

42. alias: Create custom shortcuts for your regularly used commands (only for that particular runtime)
    a. alias {destination_value} = "{source_value}"

43. whereis: Locate the binary, source, and manual pages for a command
44. whatis: Find what a command is used for

45. top: View active processes live with their system usage
    a. btop

46. --help
47. code . : to open VS Code from the terminal
48. clt+shift+v = to paste in terminal
