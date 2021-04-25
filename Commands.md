# netstat
https://www.lifewire.com/using-netstat-command-on-mac-4176069

# Linux's free -> ??

# top
Views stats about each PID

# kill 
https://ss64.com/osx/kill.html

# jsp
https://docs.oracle.com/javase/7/docs/technotes/tools/share/jps.html

# cd
Move between directories
```bash
cd [ -qsLP ] [ arg ]
cd [ -qsLP ] old new # Change old to new in the current directory name and cd to it
cd [ -qsLP ] {+|-}n
```

# mkdir
<img width="1596" alt="image" src="https://user-images.githubusercontent.com/45315180/112747937-d2e66100-8fb8-11eb-8ae1-4ae7ee6793de.png">

# rm
<img width="1592" alt="image" src="https://user-images.githubusercontent.com/45315180/112748081-c9112d80-8fb9-11eb-83c8-80a943d6fde2.png">

# cp
https://www.geeksforgeeks.org/cp-command-linux-examples/

# mv
<img width="1587" alt="image" src="https://user-images.githubusercontent.com/45315180/112750395-ac302680-8fc8-11eb-815d-297d42d4ff36.png">

# df (free disk space)
https://www.geeksforgeeks.org/df-command-linux-examples/
```bash
df -h
```

# du
<img width="1589" alt="image" src="https://user-images.githubusercontent.com/45315180/112751341-bc96d000-8fcd-11eb-8556-871109044616.png">

# echo (print input)
```bash
echo [-n] [string ...]
```

# lsof
docs

## View all listening tcp ports
```bash
lsof -PiTCP -sTCP:LISTEN
```

# Last modfied file in a directory
```bash
ls -t | head -n1
```
# Process Status
```bash
ps
```
https://www.geeksforgeeks.org/ps-command-in-linux-with-examples/

# chmod (Change files/directories permissions)
https://www.computerhope.com/unix/uchmod.htm

# chown (Change files/directories owner)
https://www.computerhope.com/unix/uchown.htm

# Head (Show first X Lines from a file)
https://www.computerhope.com/unix/uhead.htm

# Tail (Show last X Lines from a file)
https://www.computerhope.com/unix/utail.htm

# Curl
https://www.computerhope.com/unix/curl.htm

# Find
https://www.computerhope.com/unix/ufind.htm

# Alias
 - Give another name to a command
```bash
alias cls=clear
```
# Diff
 - Compares two text files
 ```bash
 diff -y -W 70 alpha1.txt alpha2.txt --suppress-common-lines
 ```
# Finger
 - Info about user
```bash
finger <user>
```
# free
 - Shows free memory duhh
```bash
free -h
```
# grep
 - Searches for lines which contain a search pattern

# groups
 - Telss you which groups a user belongs to

# gzip
 - zips files
 - use `-k` to retain the original file too
```bash
gzip -k <fileName>
```
# history
 - Show history of commands
 - Use ! <number> to redo command
 - Use !! to redo last command

# passwd
- Lets you change password for a user

# ping
 - Lets you verify that you have network connectivity with another network device
```bash
ping -a 192.168.1.1
```

# tar
 - create an archive file
 - (-z) for faster compression or (-j) for superior slower compression
```bash
tar -cvzf <archiveName>.tar.gz <dir>/
```
 - Extract an archive file using:
 - Use (-z) to extract from a ".tar.gz" archive
 - Use (-j) to extract from a ".tar.bz2" archive
```bash
tar -xvf <archiveName>.tar
```

# whoami
 - find the current logged user

# w
 - lists the current logged in users

# uname
 - List system info
   - Use  -a (all) option to see everything.
   - Use  -s (kernel name) option to see the type of kernel.
   - Use  -r (kernel release) option to see the kernel release.
   - Use  -v (kernel version) option to see the kernel version.
