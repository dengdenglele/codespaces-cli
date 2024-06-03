Hello, world!
```bash
echo 'Hello, world!'
```

Stop (SIGINT) any running foreground process in terminal with keypress:
```bash
# Ctrl+C
```

Don't get lost
```bash
whoami
echo $USER
pwd
echo $PWD
clear
# Ctrl+L works similarly like "clear"
```

Update, list and install packages with apt
```bash
sudo apt update && sudo apt upgrade -y
apt list --installed
sudo apt install cmatrix
sudo apt install htop cowsay fortune neofetch tldr ncal
```

Fun stuff
```bash
cal
cowsay 'Mooooooooooooooohhhh1!!111!!'
fortune
fortune | cowsay -f tux
cmatrix
```

Learn all about packages
```bash
whatis cal
whereis cal
which cal
type -a cal
```

Learn all about commands
```bash
man cal
tldr cal
```

Get to know your pc
```bash
top
htop
free -h
df -h
ps aux
uname -a
echo $LANG
neofetch
lsb_release -a
```

Change directory
```bash
cd
cd ~
cd ..
cd -
cd /
cd /path/to/another/directory/
```



Display directory content
```bash
ls
ls -l
ls -a
ls -a -l
ls -al
ls -la
```

Create empty file(s)
```bash
touch file1 file2 file3
touch notes_{3..6}-{w..z}
```

Open a file and edit it
```bash
nano myTextFile
vim anotherTextFile
```

View a file
```bash
cat myTextFile
less showTextFileButScrollable
head firstTenLinesOfTextFile
tail lastTenLinesOfTextFile
```

Copy, move and remove files
```bash
cp /path/of/original/file /path/to/new/destination/
mv /old/path/file /new/path/
rm oneFile anotherFile aThirdFile
# use the -i flag to make the commands interactive/less "dangerous"
```

Create directory/directories
```bash
mkdir directory1 directory2 and many more directories
mkdir {2024..2030}_{1..12}_photos-collection
```

Delete an empty directory
```bash
rmdir emptyDirectoryName 
```

Start gitk and do not let it block the terminal with ampersand (&)
```bash
gitk &
```

Open a bash inside bash and exit bash
```bash
bash
exit
```
