( je suppose que les commandes css ne vous interesse pas vraiment, de
plus vous pourrez les voirs directement )

# Liste des commandes git: #

```bash

apt install git

git --version

```
etapes pour si jamais git n'etait pas installer et une verification 
qu'il est bien installer

```bash

cd Documents
mkdir css
nano Baisset_nicolas_commandes.md
cd css
nano style.css
cd..
remote add origin https://github.com/ORyonRix/evaluationvladislavnicolasgabriel.git
git config user.name "nicokijoue"
git config user.email "nicokijoue@gmail.com"
git branch
git status
```
probleme je voyais aucune branche etc

```bash 
git branch css
```
je ne pouvais pas creer la branche non plus

```bash
nano teste
add *
git commit -m "test nico"
git push -u origin master
```
push non possible car probleme de liaison de document

```bash
git pull origin master
```
donc je recupere les fichier et la branche master
Puis je creer ma branche

```bash
git branch
git branch css
git checkup css
```
envoie du css ( apres ça creation )

```bash
git add *
git commit -m "creation du css"
git push -u origin css
```
maintenant la creation du HTML

```bash
mkdir site_web
mkdir html
nano site_web
git add site_web
git commit -m "creation du html"
git push -u origin site_web
```
entre temps j'ai aussi fait un autre commit pour la modif du html

maintenant, il y a un autre probleme, le pull ne marche pas, probleme de branche divergente.

