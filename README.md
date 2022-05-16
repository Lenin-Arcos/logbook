# 👋😁😃 Bienvenidos a mi LogBook 😃😁👋
___

![Logbook](https://www.youracsa.ca/wp-content/uploads/ACSA-Daily-Logbook.png)
### Información
Mi nombre es Lenin, usuario de GitHub @Lenin Arcos, estudiante de *1º en Sistemas de Telecomunicación e Informáticos* realizando el curso en [*IES Antonio José Cavanilles*](http://www.cavanilles.org/) año lectivo **2021-2022**

### Introducción
Realizar un logbook del curso para poder transcribirlo en GiyHub mediante Git, para poder conocer los comandos y tener conocimientos de ellos.

### Cómo crear las carpetas y Configuración de comandos Git *(terminal)*
```
nusa_@DESKTOP-E28A9KA MINGW64 ~
$ git --version
git version 2.36.1.windows.1

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ git config --global user.name "Lenin Arcos"

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ git config --global user.email "correo"

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ git config --global core.editor "code --wait"

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ git config --global -e

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Digital_2022-02-16_18-34-47.log
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 Impresoras@
 Links/
'Menú Inicio'@
'Mis documentos'@
 Music/
 NAND.circ
 NTUSER.DAT
 NTUSER.DAT{1a29ea3c-1e0a-11ec-9d2d-88b111955c5d}.TM.blf
 NTUSER.DAT{1a29ea3c-1e0a-11ec-9d2d-88b111955c5d}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{1a29ea3c-1e0a-11ec-9d2d-88b111955c5d}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
'VirtualBox VMs'/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 primera-evaluación/
 pseint/

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ mkdir logbook

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Digital_2022-02-16_18-34-47.log
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 Impresoras@
 Links/
'Menú Inicio'@
'Mis documentos'@
 Music/
 NAND.circ
 NTUSER.DAT
 NTUSER.DAT{1a29ea3c-1e0a-11ec-9d2d-88b111955c5d}.TM.blf
 NTUSER.DAT{1a29ea3c-1e0a-11ec-9d2d-88b111955c5d}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{1a29ea3c-1e0a-11ec-9d2d-88b111955c5d}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
'VirtualBox VMs'/
 logbook/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 primera-evaluación/
 pseint/

nusa_@DESKTOP-E28A9KA MINGW64 ~
$ cd logbook

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook
$ git init
Initialized empty Git repository in C:/Users/nusa_/logbook/.git/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls -a
./  ../  .git/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ code .

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
README.md

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git add README.md

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git commit -m "primera confirmación de commit"
[master (root-commit) cb67027] primera confirmación de commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git status
On branch master
nothing to commit, working tree clean

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ mkdir Primera-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ cd Primera-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Primera-Evaluación (master)
$ code .

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Primera-Evaluación (master)
$ ls

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Primera-Evaluación (master)
$ ls -la
total 0
drwxr-xr-x 1 nusa_ 197609 0 May 15 21:16 ./
drwxr-xr-x 1 nusa_ 197609 0 May 15 21:14 ../
-rw-r--r-- 1 nusa_ 197609 0 May 15 21:16 .gitignore

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Primera-Evaluación (master)
$ ls -a
./  ../  .gitignore

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Primera-Evaluación (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

nothing added to commit but untracked files present (use "git add" to track)

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Primera-Evaluación (master)
$ cd ..

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ mkdir Segunda-Evaluacón

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md  Segunda-Evaluacón/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ cd Segunda-Evaluación
bash: cd: Segunda-Evaluación: No such file or directory

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git mv Segunda-Evaluacón Segunda-Evaluacón
fatal: can not move directory into itself, source=Segunda-Evaluacón, destination=Segunda-Evaluacón/Segunda-Evaluacón

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md  Segunda-Evaluacón/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git mv Segunda-Evaluacón Segunda-Evaluación
fatal: source directory is empty, source=Segunda-Evaluacón, destination=Segunda-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md  Segunda-Evaluacón/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git mv Segunda-Evaluacón Segunda-Evaluación
fatal: source directory is empty, source=Segunda-Evaluacón, destination=Segunda-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git rm Segunda-Evaluacón
fatal: pathspec 'Segunda-Evaluacón' did not match any files

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git rm /Segunda-Evaluacón
fatal: C:/Program Files/Git/Segunda-Evaluacón: 'C:/Program Files/Git/Segunda-Evaluacón' is outside repository at 'C:/Users/nusa_/logbook'

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git -help
unknown option: -help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git mv Segunda-Evaluacón Segunda-Evaluación
fatal: source directory is empty, source=Segunda-Evaluacón, destination=Segunda-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md  Segunda-Evaluacón/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ code .

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md  Segunda-Evaluación/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ cd Segunda-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Segunda-Evaluación (master)
$ code .

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Segunda-Evaluación (master)
$ cd ..

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ mkdir Tercera-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ ls
Primera-Evaluación/  README.md  Segunda-Evaluación/  Tercera-Evaluación/

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ cd Tercera-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Tercera-Evaluación (master)
$ code .

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Tercera-Evaluación (master)
$ ls

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Tercera-Evaluación (master)
$ ls -a
./  ../  .gitignore

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Tercera-Evaluación (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "../Primera-Evaluaci\303\263n/"
        "../Segunda-Evaluaci\303\263n/"
        ./

nothing added to commit but untracked files present (use "git add" to track)

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook/Tercera-Evaluación (master)
$ cd ..

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "Primera-Evaluaci\303\263n/"
        "Segunda-Evaluaci\303\263n/"
        "Tercera-Evaluaci\303\263n/"

nothing added to commit but untracked files present (use "git add" to track)

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git add Primera-Evaluación Segunda-Evaluación Tercera-Evaluación

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   "Primera-Evaluaci\303\263n/.gitignore"
        new file:   "Segunda-Evaluaci\303\263n/.gitignore"
        new file:   "Tercera-Evaluaci\303\263n/.gitignore"


nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git commit -m "estructura de carpetas de evaluación"
[master 37c24f2] estructura de carpetas de evaluación
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 "Primera-Evaluaci\303\263n/.gitignore"
 create mode 100644 "Segunda-Evaluaci\303\263n/.gitignore"
 create mode 100644 "Tercera-Evaluaci\303\263n/.gitignore"

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git remote add origin https://github.com/Lenin-Arcos/logbook.git

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Lenin-Arcos/logbook.git'

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 565 bytes | 141.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Lenin-Arcos/logbook.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

nusa_@DESKTOP-E28A9KA MINGW64 ~/logbook (master)
$
```
### Link de videos para poder utilizar los comandos que me han sido útiles
* GIT
![Git](https://th.bing.com/th/id/R.0018de6e022d0825709fb92209d22dcc?rik=U1q0uu9SZVmqVg&riu=http%3a%2f%2fwww.foolegg.com%2fwp-content%2fuploads%2f2013%2f07%2fGit-Logo.png&ehk=XchI0GDRmcTQH2n0xvhnQNjpWxq7Np%2bZSF038c9jxgk%3d&risl=&pid=ImgRaw&r=0)
1. [Curos de Git desde cero](https://www.youtube.com/watch?v=VdGzPZ31ts8)
2. [Curos de Git desde cero](https://www.youtube.com/watch?v=HiXLkL42tMU)
* MARKDOWN

![Markdown](https://th.bing.com/th/id/R.e0f4d8f3a19d9069bc6a54959d750b4b?rik=cpS%2bd4LB5kDfiw&pid=ImgRaw&r=0)
1. [Curso de Markdown desde cero](https://www.youtube.com/watch?v=oxaH9CFpeEE)
2. [Markdown en 5 minutos](https://www.youtube.com/watch?v=y6XdzBNC0_0)

:trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface:
