# Documentation du tuto GitHub avec Git

## Initialisation du dépôt.
```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit (bonnes pratiques)

```
Titre du commit

Description de notre commit avec des informations sur l'évolution du projet.
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Titre du commit"
git push origin main
```

## Création d'une branche

```bash
git checkout -b nom_de_la_branche
```