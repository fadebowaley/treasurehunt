# Linux Basic Commands Exercises for Beginners

## Project 1: Navigating the Filesystem

### Scenario:
You have just logged into your Linux system and need to navigate through the filesystem to find a specific file named `treasure_map.txt`.

### Challenge:
1. Print the current working directory.
2. List the contents of the current directory.
3. Change to the `/home` directory.
4. List the contents of the `/home` directory.
5. Find the file `treasure_map.txt` and print its location.

### Hint:
```
1. Print the current working directory:
   ```bash
   pwd
   ```
2. List the contents of the current directory:
   ```bash
   ls
   ```
3. Change to the `/home` directory:
   ```bash
   cd /home
   ```
4. List the contents of the `/home` directory:
   ```bash
   ls
   ```
5. Find the file `treasure_map.txt` and print its location:
   ```bash
   find /home -name treasure_map.txt
   ```
```

## Project 2: Managing Files and Directories

### Scenario:
You need to organize your files and directories for a research project. This involves creating directories, moving files, and deleting unnecessary files.

### Challenge:
1. Create a directory named `research`.
2. Move into the `research` directory.
3. Create an empty file named `notes.txt`.
4. Create a subdirectory named `data`.
5. Move `notes.txt` into the `data` subdirectory.
6. Delete the `notes.txt` file from the `data` subdirectory.

### Hint:
```
1. Create a directory named `research`:
   ```bash
   mkdir research
   ```
2. Move into the `research` directory:
   ```bash
   cd research
   ```
3. Create an empty file named `notes.txt`:
   ```bash
   touch notes.txt
   ```
4. Create a subdirectory named `data`:
   ```bash
   mkdir data
   ```
5. Move `notes.txt` into the `data` subdirectory:
   ```bash
   mv notes.txt data/
   ```
6. Delete the `notes.txt` file from the `data` subdirectory:
   ```bash
   rm data/notes.txt
   ```
```

## Project 3: Viewing and Editing Files

### Scenario:
You have a file named `artifact_info.txt` containing important information about discovered artifacts. You need to view and edit this file using basic Linux commands.

### Challenge:
1. View the contents of the file `artifact_info.txt`.
2. Append the text "New artifact discovered" to the file.
3. Display the last 5 lines of the file.
4. Count the number of lines in the file.

### Hint:
```
1. View the contents of the file `artifact_info.txt`:
   ```bash
   cat artifact_info.txt
   ```
2. Append the text "New artifact discovered" to the file:
   ```bash
   echo "New artifact discovered" >> artifact_info.txt
   ```
3. Display the last 5 lines of the file:
   ```bash
   tail -n 5 artifact_info.txt
   ```
4. Count the number of lines in the file:
   ```bash
   wc -l artifact_info.txt
   ```
```

## Project 4: Managing Processes

### Scenario:
Your system is running several processes, and you need to monitor and manage these processes to ensure optimal performance.

### Challenge:
1. Display a list of all running processes.
2. Find the process ID (PID) of a process named `research_daemon`.
3. Kill the process `research_daemon` using its PID.
4. Verify that the process has been terminated.

### Hint:
```
1. Display a list of all running processes:
   ```bash
   ps aux
   ```
2. Find the process ID (PID) of a process named `research_daemon`:
   ```bash
   pgrep research_daemon
   ```
3. Kill the process `research_daemon` using its PID (replace `<PID>` with the actual PID):
   ```bash
   kill <PID>
   ```
4. Verify that the process has been terminated:
   ```bash
   pgrep research_daemon
   ```
```

## Project 5: Using Basic Networking Commands

### Scenario:
You need to troubleshoot network connectivity issues on your Linux system by using basic networking commands.

### Challenge:
1. Display the IP address of your system.
2. Display the network interfaces on your system.
3. Ping the website `www.example.com` to check connectivity.
4. Display the routing table.

### Hint:
```
1. Display the IP address of your system:
   ```bash
   ifconfig
   ```
2. Display the network interfaces on your system:
   ```bash
   ip link show
   ```
3. Ping the website `www.example.com` to check connectivity:
   ```bash
   ping www.example.com
   ```
4. Display the routing table:
   ```bash
   netstat -rn
   ```
```

---

These exercises will provide you with practical experience using basic Linux commands and help you develop a solid understanding of fundamental Linux operations.
