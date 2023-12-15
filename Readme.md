# Git verziókezelés

## Helyi repo létrehozása

- a helyi repo inicializálása:
    > git init
- ellenőrzés:
    > git status
- előkészítjük a kommitolásra (beindexelődnek-stage):
    > git add .
- ellenőrzés:
    > git status
- username, email ellenőrzése:
    > git config user.name

    >git config user.email
- létrehozzuk a legújabb verziót, eltároljuk a helyi repoba:
    > git commit -m "first commit"
- ellenőrzés:
    > git status

## Összekapcsolás a távoli repoval

- új GitHub repo létrehozása (publikus)
- összekapcsolási parancs:
    > git remote add origin https://token@github.com/mkatay/**repoName**.git
- az első alkalommal meg kell mondani az ágat, hogy hová kerüljön:
    > git push -u origin master
- kérni fogja a tokent, amit a privát repóban eltároltál