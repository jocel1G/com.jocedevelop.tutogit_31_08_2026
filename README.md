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
git commit -m "Un commentaire"
git push origin main
```

## Création d'une branche

```bash
git checkout -b nom_de_la_branche
```

Pour les bonnes pratiques, on va intégrer la notion de revue de code. Pour cela, on va créer une branche pour chaque fonctionnalité que l'on souhaite ajouter à notre projet. Une fois la fonctionnalité terminée, on va créer une Pull Request (PR) pour demander à un autre développeur de relire notre code avant de le fusionner dans la branche principale.