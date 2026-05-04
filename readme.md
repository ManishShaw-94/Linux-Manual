# LINUX MANUAL

> A **kernel** is a program that allocates and controls hardware resources in a system. A kernel acts as an interface between your raw hardware (RAM, processor, storage) and the operating system.

> **Linux** is a kernel upon which you can build an operating system (also called Linux distributions, for example: Ubuntu, Alpine, Fedora). Linux distributions use the Linux kernel together with the GNU operating system.

---------------------------

**Basic Linux Commands**

--------------------------

**1. ls:**  List directories
   
    a. ls -a : List all directories including hidden ones
   
    b. ls -l : Show detailed information
   
    c. ls -la: Detailed information including hidden files

**2. pwd:** Print working directory

**3. cd:** Navigate through directories
   
    a. cd .. : Go back one directory
   
    b. cd - : Go back to the last directory

**4. mkdir:** Create directories in Linux

**5. mv:** Move or rename files in Linux
   
    example: mv {source_file_name} {target_destination}
   
    example: mv {current_file_name} {new_file_name}

**6. cp:**  Copy files in Linux
    
    example: cp {source_file_name} {destination_with_file_name} 

**7. rm:** Delete files or directories
    
    a. rm {file_name} : Delete a single file
    
    b. rm -rf {directory_name} : Delete a folder recursively (use carefully)

**8. touch:** Create empty files

**9. ln:** Create symbolic links (shortcuts) to other files
    
    example: ln -s {source_file_name} {destination_with_file_name} 

**10. cat:** Display file contents on the terminal

**11. clear:** Clear the terminal display

**12. echo:** Print any text that follows the command

**13. man:** Access manual pages for linux commands

**14. uname:** Get system information

    a. uname -mrs : Information about the OS (OS name, kernel version, processor)
    
    b. uname -a : Detailed system information 

**15. whoami:** Show current user

**16. tar:** Compress and extract files
    
    example to create a tar folder: tar -cvf {destination_folder_name} {source folder name}
    
    example to extarct a tar folder: tax -xvf {folder_name}

**17. grep:** Search for text within an output
    
    example: cat {file_name} | grep {output_string}
    
    example: cat {file_name} | grep {output_string} -n
    
    example: ps | grep {output_string}

**18. head:** Show first lines of a file
    
    example: head {file_name}
    
    example: head -n 5 {filename} <- Returns first 5 lines

**19. tail:** Show last lines of a file

**20. printenv:** Show environment variables

**21. export:** Set environment variables (temporary - only for that particular runtime)
    
    exmaple: export name={name_which_you_want_to_give}

**22. zip:** Zip files

    example: zip {source_folder_name} {destination_folder_name} 

**23. unzip:** Unzip files

    example: unzip {source_folder_name.zip} -d {destination_folder_name}

**24. ssh:** Secure shell (remote login)

**25. service:** Manage services (services are collection of task)
    
    a. service --status-all : to get all the services

**26. ufw:** Firewall management

**27. ps:** Show running processes (processes are task)
    
    a. ps aux : all the running tasks

**28. kill** and **killall:** Stop active processes (by process ID or name)

**29. df:** Show disk filesystem information
    
    a. df -h

**30. chmod:** Change file permissions (r = read, w = write, x = executable)
    
    example: chmod +x {application_name} <- making application executable
    
    example: chmod 777 {application_name} <- giving application all possible permissions (not recommended)

**31. ifconfig:** Show network interfaces and IP addresses

**32. curl:** Send HTTP requests and fetch data from it

**33. wget:** Download files from internet

**34. sudo:** Execute commands with elevated privileges

**35. apt, pacman, yum, rpm** - Package manager depending on the distro
    (**snap** - Ubuntu package manager)
    
    example: sudo apt install {application_name}
    
    example: sudo apt remove {application_name}
    
    example: sudo apt update
    
    example: sudo apt upgrade

**36. alias:** Create command shortcuts (temporary - only for that particular runtime)
    
    a. alias {destination_value} = "{source_value}"

**37. whereis:** Locate command files (binary, source, and manual pages for a command)

**38. whatis:** Describe a command

**39. top:** Monitor system processes

    a. btop

**40. vim:** Terminal based text editor to create or edit files

   a. :wq : To save and exit from text editor

**41. bash:** To open a new shell/terminal

**42. --help:** Show command help

**43. code .** Open VS Code in current directory

**44. clt+shift+v**  Paste in terminal
