# Linux commands cheat-sheet!

## Basic Commands

### touch
#### This creates a new empty file.
```
touch emptyFile.txt
```

### ls
#### This command is used to list the files and directories under your present working directory (pwd)
```
ls
```
 There are many options you can use with ```ls``` to get relevant data that you require. Run ```ls --help ``` and explore the options available with ```ls```


### pwd
#### This commands tells you which directory are you presently working on
```
pwd
```


### cd
#### This command is used to enter a particular directory of your choice
```
cd /home/user/testDir -------->>>> for absolute paths
cd testDir ------------->>>>>>>>>> for relative paths
```

### mkdir

#### This creates a new directory.
```
mkdir /home/user/testDir -------->>>> for absolute paths
mkdir testDir ------------->>>>>>>>>> for relative paths
```

### cp
#### This command copies a file or a directory from source location to a target location.
```
cp /source_location /target_location ----> For files
cp -r /source_location /target_location ---> For directory
```

### rm
#### This command is to remove file or a directory from your system
 
 To remove a file, use this command.
```
rm /home/userme/sample.txt -------->>>> for absolute paths
rm sample.txt -------------->>>>>>>>>>> for relative paths
```
To remove a directory, use these commands (make sure you have the necessary permissions!)
```
rm -rf /home/userme/testDir-------->>>> for absolute paths
rm -rf testDir -------------->>>>>>>>>> for relative paths
```

### whoami
This commands tells us which is the current user.
```
$ whoami
>user
```

### id
This gives us the user id, group ids and the relevant group ids attached to user
```
id
```
### ssh
This allows us to access another system or user of another system.
```
SSH user@123.168.1.2
```

### sudo
this is the root user which has all permissions and data. for performing any sudo-related command, do
```
sudo apt-get update
sudo ls /root
```

### curl
This is used to download the files from url and -O is used to save files.
```
curl https://www.some-site.com/some-file.txt -O
```

### wget
This is also used to download the files from url and -O is used to save files.
refer to this [{[Difference Between wget VS curl - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-wget-vs-curl/)} for understanding the difference.
```
wget https://www.some-site.com/some-file.txt -O some-file.txt
```

### Check OS Version
```
ls /etc/*release*
cat /etc/*release*
```



