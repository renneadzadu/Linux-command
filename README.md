# Linux-command (use git bash)

# file system

what is Linux = it is inbeded in all computers. powered by PARROT OS. type: LINUX KERNEL. Linux is an open source. everything is a file. the dev(device) is a file.
commands are files
/- = root dirctory
cat = (stand for concatenate) prints all binary(computer form of communicating) codes
cat ls = if you use cat on any other files, it will print out all the binary codes EX: cat ls (will print binary codes for ls)
whoami = commad that tells you your destop and username
/bin = binary files which holds commands such as ls, pwd, cd,rm,and more
/sbin =  System binaries. super bin for administration use. holds command such as "adduser"
which = tells you which file you are using. ex: /bin or /usr
usr = has same commad as (bin & sbin)
mnt = (you must use the command to mount manually) mount  
media = (mounts by default automatically ) like flash drive plugged in will automatically be mnt to the media 
/lib – Shared libraries
/tmp – Temporary files
/boot – Boot files =  contains the files of the kernel and boot image


# command Line

cp = copy file into new or another file name 
rm or sudo rm = remove file
cd = (change dir) takes you into a specified file
cd .. = takes you back as much as it can. you can cd .. so much to end up in your \ root directory
dir = serves as ls(List directory) for windows
ls = List Dir
ls -a = command used to show hidden file
ls -l = shows a detailed list of files in a long format
pwd = (takes you to working dir)
echo Hello World = prints hello world
touch = allows you to the create new empty files
file = used to find file type for files
less - condense large files
clear = clears the teminal
mv = moves file  ex: move catffile.png to dogfile.png ( mv catffile.png  dogfile.png)
mkdir = makes directory
Help echo = This will give you a description and the options you can use when you want to run echo.
Whatis = used to see a describtion of a command
 exit = tab out
 logout = signs you out




  # git
  hash function =every git object has its own unique hash.
  Repository = where files are 
  working directory = current working folders
  staging area = added files ready to commit
  git repository = files in the github
  git add = staging
  git add . = adds all working repository
  git commit = commits changes (when file is commited, git saves author name and email and assignes unique hash)
  ? how to set author name and email for git = git config -- global user.name <Name> , git config -- global user.email <email>
 git config --list = to check if you already config email and name to git
 git global --edit = use to edit your global config. I= to insert , esc :wq to quit out.
 git log = check history of all commits
 git checkout = checkout commit or branch
 
 
   # branching and merging
 git branch renne = created a beranch called renne 
 git checkout renne = in a branch called renne 
 git  log = will show HEAD - main, renne branch
 git log -- graph = shows tree of parent branch and child branch

  
