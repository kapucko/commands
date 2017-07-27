# commands
 In this file I'm going to collect usefull(at least for me) Linux(mostly for debian) commands and dummy config files
 
## Linux
 Compress file/directory to .tar.gz:
 ```
 tar --exclude='./directory-or-file' -czvf name-of-archive.tar.gz /path/to/directory-or-file
 ```
 Extract .tar.gz file:
 ```
 tar -zxvf backup.tar.gz
 ```

 Create dedicated user for app:
 ```
 useradd --system --gid <group_name> --shell /bin/bash --home <path_to_existing_folder> <user_name>
 ```
 Force time (needs sudo):
 ```
 date -s "31 JUL 2017 23:59:00"
 ```
