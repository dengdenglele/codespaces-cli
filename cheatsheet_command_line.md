Change directory
```bash
cd
cd ~
cd ..
cd -
cd /
cd /path/to/directory/name
```

Update, list and install stuff with apt
```bash
sudo apt update && sudo apt upgrade -y
apt list --installed
sudo apt install cmatrix
sudo apt install htop cowsay fortune neofetch tldr 
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

Don't get lost
```bash
whoami
pwd
whatis
whereis
which
man
tldr
type -a
clear
```

Display directory content
```bash
ls
ls -l
ls -a
ls -a -l
ls -al
ls -la

Open a bash inside bash and exit bash
```bash
bash
exit
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
cp
mv
rm
# use the -i flag to make the commands interactive/less "dangerous"
```

Delete an empty directory
```bash
rmdir 
```

Open a file and edit it
```bash
nano myTextFile
vim anotherTextFile
```

Create empty file(s)
```bash
touch file1 file2 file3
touch notes_{3..6}-{w..z}
```

Create directory/directories
```bash
mkdir directory1 directory2 and many more directories
mkdir {2024..2030}_{1..12}_photos-collection
```

Fun stuff
```bash
cal
cowsay
cmatrix
fortune
```

Stop (SIGINT) the process with keypress:
```bash
Ctrl+C
```

Start gitk and do not let it block the terminal with ampersand (&)
```bash
gitk &
```

