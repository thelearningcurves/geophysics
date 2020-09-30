# ASSIGNMENT- Basic Unix commands

> submitted to : Raghav Singh
>
> Department of Geophysics
>
> Banaras Hindu University

---------



Here, I have  Data.txt file on my windows desktop. Since I am using WSL on ubuntu terminal, to copy a file from any windows drive I would have to mount that drive like we usually do for a floppy or removable drive on a Unix or Linux platform.

```bash
thefatbuddha@DESKTOP-C9MEP3Q:~$ mkdir testfile
thefatbuddha@DESKTOP-C9MEP3Q:~$ mkdir "test file"

```

This creates a new directory in the HOME directory. If someone wants a name with a space in between, then put the desired name in a "  " as show in second line.

```bash
thefatbuddha@DESKTOP-C9MEP3Q:~$ cd /mnt/c/users/Shivoham/desktop
thefatbuddha@DESKTOP-C9MEP3Q:/mnt/c/users/Shivoham/deskop$ cp data.txt $HOME/testfile

```

We can either first go to the desktop my mounting the C drive on the terminal and then copying the required file to a newer destination. Here the file is copied to the newly created directory 'testfile' in the home directory.

```bash
thefatbuddha@DESKTOP-C9MEP3Q:~$ cd testfile
thefatbuddha@DESKTOP-C9MEP3Q:~/testfile/$ awk '$4 >45' data.txt

```

AWK is a powerful text processor that can do complex tasks with simple lines of coding. the coding format for providing instruction is usually that of C.

The above command will provide all the rows of the text file where the value in 4th field or 4th column is greater than 45.