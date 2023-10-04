# Git verziókezelés

## Helyi repo létrehozása

- helyi repo inicializálása:
    > git init
- ellenőrzés:
    > git status
- előkészítjük a commit-ra(a verzió létrehozására):
    > git add .
- ellenőrzés:
    > git status
- commit:
    > git commit -m "first commit"
- a commit-ok listázása:
    > git log

## Helyi repo összekapcsolása a távoli repoval

- távoli repo létrehozása
- helyi repo összekapcsolása a távolival
    > git remote add origin ...token@github.com...
- a legelső alkalommal a push:
    > git push -u origin master
- a továbbiakban:
    > git push