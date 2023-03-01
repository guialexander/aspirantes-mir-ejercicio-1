Alexander.Herrera@COLB002 MINGW64 ~ (master)
$ mkdir ejercicios

Alexander.Herrera@COLB002 MINGW64 ~ (master)
$ cd ejercicios/

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ pdw
bash: pdw: command not found

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ pwd
/c/Users/Alexander.Herrera/ejercicios

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ mkdir ejercicio1

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ cd ejercicio1/

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios/ejercicio1 (master)
$ touch README.md

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios/ejercicio1 (master)
$ cd ..

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ git init
Initialized empty Git repository in C:/Users/Alexander.Herrera/ejercicios/.git/

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ git config --global Alex.Herrera Alex Herrera

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ git config --global Alex.guialexander@gmail.com guialexander@gmail.com
warning: alex.guialexander@gmail.com has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change Alex.guialexander@gmail.com.

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ git add .

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ git commit -m "Versión Inicial"
[master (root-commit) 360f17f] Versión Inicial
 Committer: Alexander Herrera <Alexander.Herrera@almundo.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md

Alexander.Herrera@COLB002 MINGW64 ~/ejercicios (master)
$ git status
On branch master
nothing to commit, working tree clean
