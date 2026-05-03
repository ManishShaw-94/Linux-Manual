# LINUX MANUAL

> A kerner is a program that allocates and controls hardware resources in a system. 
    A kernel act as an interface between your raw hardware (RAM, processor, storage) and the Operating System.

> A linux is a kernel upon which you can build an Operating System (also called Linux Distros, say for example: Ubuntu, Alpine, Fedora).
    Linux Distribution use the Linux Kernel together with the GNU Operating System.

---------------------------

**Basic Linux Commands**

--------------------------

**1. ls:**  To list directories
   
    a. ls -a : To list all directories including hidden ones
   
    b. ls -l : More details about each of the directories
   
    c. ls -la: More details about each of the directories including hidden ones

**2. pwd:** Print working directories

**3. cd:** To navigate through directories
   
    a. cd .. : to go back one directory
   
    b. cd - : to go back to the last directory you were on

**4. mkdir:** To make directories in linux

**5. mv:** Move or rename file in linux
   
    example: mv {source_file_name} {target_destination}
   
    example: mv {current_file_name} {new_file_name}

**6. cp:**  Coping files in linux
    
    example: cp {source_file_name} {destination_with_file_name} 

**7. rm:** Delete files or directories
    
    a. rm {file_name} ; to delete a single file
    
    b. rm -rf {directory_name} : remove recursively by force to delete a folder

**8. touch:** Create blank/empty files

**9. ln:** Create symbolic links (shortcuts) to other files
    
    example: ln -s {source_file_name} {destination_with_file_name} 

**10. cat:** Display file contents on the terminal

**11. clear:** Clear the terminal display

**12. echo:** Print any text that follows the command

**13. man:** Access manual pages for all linux commands

**14. uname:** To get the basic information about the OS

    a. uname -mrs : to get more information about the OS (OS name, kernel version, processor type)
    
    b. uname -a : to get extra more information about the OS 

**15. whoami:** Get the active Username

**16. tar:** To extract and compress files in linux
    
    example to create a tar folder: tar -cvf {destination_folder_name} {source folder name}
    
    example to extarct a tar folder: tax -xvf {folder_name}

**17. grep:** Search for a string within an output
    
    example: cat {file_name} | grep {output_string}
    
    example: cat {file_name} | grep {output_string} -n
    
    example: ps | grep {output_string}

**18. head:** Return the specific number of lines from the top
    
    example: head {file_name}
    
    example: head -n 5 {filename} <- Returns first 5 lines

**19. tail:** return the specific number of lines from the bottom

**20. printenv:** to print all the environment variables

**21. export:** Export environment vaiables in linux (only for that particular runtime)
    
    exmaple: export name={name_which_you_want_to_give}

**22. zip:** Zip files in linux

**23. unzip:** Unzip files in linux

**24. ssh:** Secure shell command in linux

**25. service:** To start and stop services (services are collection of task)
    
    a. service --status-all : to get all the services

**26. ufw:** Firewall command

**27. ps:** Display active processes (processes are task)
    
    a. ps aux : all the running tasks

**28. kill** and **killall:** Kill active processes by process ID or name

**29. df:** Display disk filesystem information
    
    a. df -h

**30. chmod:** Command to change file permission (r = read, w = write, x = executable)
    
    example: chmod +x {application_name} <- making application executable
    
    example: chmod 777 {application_name} <- giving application all possible permissions (not recommended)

**31. ifconfig:** Display network interfaces and IP addresses

**32. curl:** to send http request and fetch data from it

**33. wget:** Direct download files from the internet

**34. sudo:** Command to esclate privilegs in Linux

**35. apt, pacman, yum, rpm** - Package manager depending on the distro
    (**snap** - Ubuntu package manager)
    
    example: sudo apt install {application_name}
    
    example: sudo apt remove {application_name}
    
    example: sudo apt update
    
    example: sudo apt upgrade

**36. alias:** Create custom shortcuts for your regularly used commands (only for that particular runtime)
    
    a. alias {destination_value} = "{source_value}"

**37. whereis:** Locate the binary, source, and manual pages for a command

**38. whatis:** Find what a command is used for

**39. top:** View active processes live with their system usage
    a. btop

**40. --help**

**41. code .** to open VS Code from the terminal

**42. clt+shift+v**  to paste in terminal
