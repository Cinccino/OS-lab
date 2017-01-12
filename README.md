# OS-lab
Labs on Android used in os course in PKU

## Lab 1: Color
Add syscall getcolors and setcolors. Helping get familiar to kernel programming.

## Lab 2: Process resource management
Add syscall getnicebypid, setnicebycolor, getquotabycolor, setquotabycolor. Manage the resourses that a (group) of process can use.

## Lab 3: Simple shared memory
Add syscall ssmem_attach and ssmem_detach, manage simple memory sharing between processes.

## Lab 4: Cloud file system
Add new function to ext2 file system. When the space of the fs is not enough, the deamon thread evict some file to the server and fetch them back when it is needed.
