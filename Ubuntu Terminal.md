<!-- #### 
    
 -->
## Basic Commands  
#### Update System
    apt-get update
#### Upgrade Full System
    apt-get full-upgrade
#### Copy
    cp <target_file_path> <destination_path>
#### Move
    mv <target_file_path> <destination_path>
#### Delete or Remove file 
    rm <file_path>
#### Remove Directory or folder
    rmdir <folder_path>
#### Remove Forcely file or folder or directory
    rm -rf <path>
#### Search Software from internet
    apt-get search <software_name>
#### Install Software from internet
    apt-get install <software_name>
#### Delete Software with data files
    apt-get purge <software_name>
#### Install Software from .deb file
    dpkg -i <software_name>
#### List of all Itemls is a folder 
    ls
#### Go to a folder 
    cd <folder_path>


## Advanced Commands
#### Failed to fetch <url>
    curl <url> | sudo apt-key add -
#### Expired GPG: Key re-generate 
    apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys <expired_key>
#### Find all expired keys
    sudo apt-key list | grep -A 1 expired
