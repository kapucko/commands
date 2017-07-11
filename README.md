# commands
 In this file I'm going to collect usefull(at least for me) Linux(mostly for debian) commands and dummy config files
 
## Linux
 Compress file/directory to .tar.gz:
 ```
 tar --exclude='./directory-or-file' -czvf name-of-archive.tar.gz /path/to/directory-or-file
 ```

 Create dedicated user for app:
 ```
 useradd --system --gid <group_name> --shell /bin/bash --home <path_to_existing_folder> <user_name>
 ```
