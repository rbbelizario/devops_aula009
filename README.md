boa noite, 

professor quebrei a cabeça tentando pelo linux , mas não consegui

criei mas me perdi.


nothing to commit, working tree clean
root@96162a476a72:/devops_aula009# .
bash: .: filename argument required
.: usage: . filename [arguments]
root@96162a476a72:/devops_aula009#
root@96162a476a72:/devops_aula009#
root@96162a476a72:/devops_aula009#
root@96162a476a72:/devops_aula009#
root@96162a476a72:/devops_aula009# ls -la
total 16
drwxr-xr-x 3 root root 4096 Oct 10 01:44 .
drwxr-xr-x 1 root root 4096 Oct 10 01:44 ..
drwxr-xr-x 8 root root 4096 Oct 10 02:11 .git
-rw-r--r-- 1 root root   16 Oct 10 01:44 README.md
root@96162a476a72:/devops_aula009# D:\Git
bash: D:Git: command not found
root@96162a476a72:/devops_aula009# CD ..
bash: CD: command not found
root@96162a476a72:/devops_aula009# cd ..
root@96162a476a72:/# d:
bash: d:: command not found
root@96162a476a72:/# cd d:\git
bash: cd: d:git: No such file or directory
root@96162a476a72:/# cd git
bash: cd: git: No such file or directory
root@96162a476a72:/# ls
bin  boot  dev  devops_aula009  etc  home  impacta  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@96162a476a72:/# cd impacta
root@96162a476a72:/impacta# ls -la
total 60
drwxrwxrwx 1 root root  4096 Oct 10 01:12  .
drwxr-xr-x 1 root root  4096 Oct 10 01:44  ..
-rwxrwxrwx 1 root root  3962 Oct 10 01:07 'criando container 2.PNG'
-rwxrwxrwx 1 root root  4080 Oct 10 01:06 'criando container.PNG'
-rwxrwxrwx 1 root root 26689 Oct 10 01:12 'instalando pacotes 2.PNG'
-rwxrwxrwx 1 root root 18951 Oct 10 01:10 'instalando pacotes.PNG'
root@96162a476a72:/impacta# add ..
bash: add: command not found
root@96162a476a72:/impacta# add .
bash: add: command not found
root@96162a476a72:/impacta# git add .
fatal: not a git repository (or any parent up to mount point /)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
root@96162a476a72:/impacta# cd..
bash: cd..: command not found
root@96162a476a72:/impacta# cd ..
root@96162a476a72:/# cd dev
dev/            devops_aula009/
root@96162a476a72:/# cd dev
root@96162a476a72:/dev# cd devops_aula009/
bash: cd: devops_aula009/: No such file or directory
root@96162a476a72:/dev# cd
console  core     fd/      full     mqueue/  null     ptmx     pts/     random   shm/     stderr   stdin    stdout   tty      urandom  zero
root@96162a476a72:/dev# ls
console  core  fd  full  mqueue  null  ptmx  pts  random  shm  stderr  stdin  stdout  tty  urandom  zero
root@96162a476a72:/dev#