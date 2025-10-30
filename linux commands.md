## LINUX COMMANDS


# 1) Package Management (Debian-based)

| Command         | Description                   | Example                             |
|-----------------|-------------------------------|-------------------------------------|
| apt update    | Update repo info              | sudo apt update                   |
| apt upgrade   | Upgrade packages              | sudo apt upgrade                  |
| apt install   | Install a package             | sudo apt install nmap             |
| apt remove    | Remove a package              | sudo apt remove apache2           |

# 2) File & Directory Commands

| Command       | Description               | Example                       |
|---------------|---------------------------|-------------------------------|
| pwd         | Show current directory    | pwd                         |
| 1s          | List files/directories    | 1s -1                       |
| 1s -1       | Detailed listing          | 1s -1                       |
| 1s -a       | Show hidden files         | ls -a                       |
| cd          | Change directory          | cd /etc                     |
| cd ..       | Go up one level           | cd ..                       |
| cd ~        | Go to home directory      | cd ~                        |
| cd -        | Go to previous directory  | cd -                        |
| mkdir       | Create directory          | mkdir testdir               |
| rmdir       | Remove empty directory    | rmdir testdir               |
| rm          | Remove files/directories  | rm file.txt , rm -r dir/  |
| touch       | Create empty file         | touch file1. txt            |
| cp          | Copy file/directory       | cp file1.txt file2.txt      |
| mv          | Move/rename file          | mv file1.txt file2.txt      |
| find        | Search for files          | find . -name " *. sh"       |


# 3) File Content Commands
| Command        | Description                    |  Example                        |
|----------------|--------------------------------|---------------------------------|
| cat          | View file content              | cat file.txt                  |
| more, less | View file with scroll          | less file.txt                 |
| head         | View first 10 lines            | head file.txt                 |
| tail         | View last 10 lines             | tail file.txt                 |
| wc           | Word/line count                | wc -1 file.txt                |
| cut          | Extract columns                | cut -d,` -f1 file.csv`        |
| sort         | Sort file lines                | sort file.txt                 |
| uniq         | Remove duplicates              | uniq file.txt                 |
| diff         | Show differences between files | diff file1 file2              |

# 4) User & Permissions

| Command          | Description                   | Example                         |
|------------------|-------------------------------|---------------------------------|
| whoami         | Show current user             | whoami                        | 
| id             | Show user/group IDs           | id                            |
| chmod          | Change permissions            | chmod 755 script.sh           |
| chown          | Change owner                  | chown root:root file.txt      |
| adduser        | Add user                      | adduser alice                 | 
| passwd         | Change password               | passwd alice                  |
| su             | Switch user                   | su -                          |
| sudo           | Run as super user             | sudo apt uppdate              |

# 5) Networking 

| Command           | Description             | Example                             |
|-------------------|-------------------------|-------------------------------------|
| ping            | Test connectivity       | ping google.com                   |
| ifconfig / ip a | View network interfaces | ip a                              |
| netstat -tuln   | View open ports         | netstat -tuln                     |
| cur1            | Fetch URLs              | curl http://example.com           |
| wget            | Download files          | wget http://file.com/file.txt     |

# 6) File Compression and Archiving

| Command         | Description               | Example                                  |
|-----------------|---------------------------|------------------------------------------|
| tar           | Archive files             | tar -cvf archive.tar file1 file2       |
| tar -xvf      | Extract tar archive       | tar -xvf archive.tar                   |
| tar -czvf     | Create gzip tar           | tar -czvf archive.tar.gz dir/          |
| gzip          | Compress file             | gzip file.txt                          |
| gunzip        | Decompress .gz          | gunzip file.txt.gz                     |
| zip           | Zip files                 | zip archive.zip file1 file2            |
| unzip         | Unzip archive             | unzip archive.zip                      |
