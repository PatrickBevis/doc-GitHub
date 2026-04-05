# Documentation Github

Cette doc à pour but de donner les commandes de bases et aussi celles plus spécifique pour une utilisation de github qui soit la meilleure possible. 

## Les commandes de bases

Installer Git (linux) :

```bash
sudo apt install git
```


Configurer Git :

```bash
git config --global user.name "YourName"
git config --global user.email "yourname@example.com"
```

Initialiser un dépot Git :

```bash
git init
```

Ajouter tout les fichiers :
```bash
git add .
```

Faire un commit :

```bash
git commit -m "First commit"
```

Envoyer les modifications :

```bash
git push
```

Mettre le projet à jour :
```bash
git pull
```

### Aller plus loin

Regarder l'état du projet : 

```bash
git status
```

Regarder l'historique :

```bash
git log
```

## Travailler avec les branches

Les branches sont surtout utiliser pour le travail d'équipe, on ne va pas directement programmer sur la branche **main**


Créer une branche :

Pour la création de branche, il existe plusieurs façon de procéder 

- Utiliser ton nom

```bash
git branch -b yourName
```
- Utiliser le type de fonctionnalité et une description de celle ci (on peut ajouter egalement le numero de ticket associé si il y a)
  
```bash
git branch -b feature/123-feature-name
```
Changer de branche :

```bash
git branch main
```
Lister les branches :
```bash
git branch
```

