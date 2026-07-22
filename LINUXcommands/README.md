## Basic Commands: 

1. ls- list directory contents
    The ls command has a variety of options to customize its output:

    -l - Long listing format
    -a - Include hidden files
    -h - Human-readable sizes
    -t - Sort by modification time
    -r - Reverse order while sorting
    -R - List subdirectories recursively
    -S - Sort by file size
    -1 - List one file per line
    -d - List directories themselves, not their contents
    -F - Append indicator (one of */=@|) to entries


2. cd- change directory
    cd ..: Move up one directory level
    cd ~: Change to the home directory
    cd -: Switch to the previous directory
    cd /: Change to the root directory

    The pwd command supports a few options to customize its output:

    -L: Display the logical current working directory
    -P: Display the physical current working directory (without symbolic links)

3. echo- print text to the terminal
    The echo command has several options to customize its output:

    -n - Don't add a new line at the end
    -e - Allow special characters like \n for new lines
    -E - Don't allow special characters (default)

4. mkdir- make directory
    The mkdir command has several options to customize its behavior:

    -p - Create parent directories as needed
    -v - Show a message for each created directory
    -m - Set file mode (permissions)

5. rm- remove file
    The rm command has options to change how it works:

    -r - Delete a folder and everything inside it
    -i - Ask before deleting each file
    -f - Force delete without asking
    -v - Verbose mode, show files being removed

6. cp- copy file
    The cp command has options to change how it works:

    -r - Copy all files and folders inside a directory
    -i - Ask before replacing files
    -u - Copy only if the source is newer
    -v - Verbose mode, show files being copied
    -m - Move instead of copy

7. mv- move file
    The mv command has options to change how it works:

    -r - Move a folder and everything inside it
    -i - Ask before replacing files
    -v - Verbose mode, show files being moved
    -n - Do not overwrite existing files

8. cat- display file contents
    The cat command has options to change how it shows text:

    -n - Add numbers to each line
    -b - Add numbers only to lines with text
    -s - Remove extra empty lines
    -v - Show non-printing characters (except for tabs and end of line)
    cat can also be used to concatenate multiple files:

    cat file1 file2 file3 > combined.txt

9. less- display file contents page by page

10. head- display first few lines of file

11. tail- display last few lines of file

12. grep- search for text in file

13. wc- count lines, words, and characters in file

14. sort- sort lines of file

15. uniq- remove duplicate lines from file

16. touch- create an empty file
    The rm command has options to change how it works:

    -r - Delete a folder and everything inside it
    -i - Ask before deleting each file
    -f - Force delete without asking
    -v - Verbose mode, show files being removed

17. less- display file contents page by page

18. head- display first few lines of file
    The head command has several options used to customize its behavior:

    -n [number]: Display the first [number] lines of the file.
    -c [number]: Display the first [number] bytes of the file.

19. tail- display last few lines of file
    The tail command has several options to customize its behavior:

    -n [number]: Display the last [number] lines of the file.
    -f: Follow the file as it grows, useful for monitoring log files.
    -c [number]: Display the last [number] bytes of the file.
    --pid=[pid]: Terminate after the process with the given PID dies.
    --retry: Keep trying to open a file even if it is inaccessible.

20. grep- search for text in file
    The grep command has options to change how it works:

    -i - Search ignoring case differences (uppercase or lowercase)
    -r - Search through all files in a directory and its subdirectories
    -v - Find lines that do not match the pattern

21. wc- count lines, words, and characters in file

22. sort- sort lines of file
    The sort command has options to change how it works:

    -r - Sort in reverse order
    -n - Sort numbers correctly
    -k - Sort by a specific column
    -u - Remove duplicate lines
    -t - Specify a delimiter for fields

23. man- display user manual of any command that can be run on the terminal.

24. alias- create shortcuts for commands

25. awk- pattern scanning and processing tool
    The awk command has options to change how it works:

    -F - Set what separates the data fields
    -v - Set a variable to be used in the script
    -f - Use a file as the source of the awk program

26. sed- stream editor for filtering and transforming text
    The sed command has options to change how it works:

    -i - Edit files directly without needing to save separately
    -e - Add the script to the commands to be executed
    -n - Don't automatically print lines
    -r - Use extended regular expressions
    -f - Add script from a file
    -l - Specify line length for l command

27. find- search for files and directories

28. cut- remove sections of each line of files
    The cut command has options to change how it works:

    -d - Choose what separates the fields
    -f - Select specific fields to display
    --complement - Show all fields except the selected ones.

29. ps- display information about running processes
    The ps command has options to change how it works:

    -e - Show all processes
    -f - Show detailed information
    -u - Show processes for a specific user
    -a - Show all processes with a terminal
    -x - Show processes without a terminal

30. kill- send signals to processes
    The kill command has several options to customize its behavior:

    -9 - Forcefully terminate a process.
    -l - List all signal names.
    -s [signal] - Specify a signal to send.
    -p - Print the process ID.

31. top- display real-time information about     processes
    The top command has options to change how it works:

    -d - Set the time between updates
    -p - Monitor specific PIDs
    -u - Show tasks for a specific user
    -n - Set the number of iterations
    -b - Batch mode operation

32. du - estimate file space usage
    The du command has options to change how it works:

    -h - Show sizes in human-readable format (e.g., KB, MB)
    -s - Show only the total size for each item
    -a - Show sizes for all files, not just directories
    -c - Produce a grand total
    --max-depth=N - Limit the depth of directory traversal

33. free- the amount of free memory and swap space on the system
    The free command has options to change how it works:

    -h - Show memory in human-readable format (e.g., KB, MB, GB)
    -b - Show memory in bytes
    -k - Show memory in kilobytes (KB)
    -m - Show memory in megabytes (MB)
    -g - Show memory in gigabytes (GB)
    -s [interval] - Continuously display memory usage at specified intervals
    -t - Display total memory

34. uptime - the amount of time the system has been running

35. ping - tool for checking network connectivity and diagnosing network problems
    The ping command has options to change how it works:

    -c - Send a specific number of ping requests
    -i - Wait a specific number of seconds between sending each packet
    -t - Set the IP Time to Live (TTL)
    -q - Quiet output, only show summary
    -s - Specify the number of data bytes to be sent

36. curl - transfer data from or to a server
    The curl command has options to change how it works:

    -O - Save the file with the same name as the remote file
    -L - Follow redirects
    -I - Fetch the HTTP headers only
    -d - Send data with POST request
    -u - Specify user and password for server authentication

37. wget - download files from the internet.
    The wget command has options to change how it works:

    -b - Run in the background
    -q - Quiet mode (no output)
    -r - Download directories recursively
    -c - Continue getting a partially-downloaded file
    --limit-rate - Limit download speed

38. ssh - secure shell client, connect to a remote server/ machine.
    -p - Specify the port
    -i - Use a private key file
    -v - Enable verbose mode
    -C - Enable compression
    -X - Enable X11 forwarding
    -o - Specify options directly on the command line

39. unzip- extract files from a ZIP archive

---------------XX---------------