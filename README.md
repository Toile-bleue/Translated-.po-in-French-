# Eventon fr_FR

Ce dépôt contient la traduction française du plugin WordPress Eventon.

## Objectif

Centraliser la traduction et permettre une maintenance collaborative du fichier `.po` pour la version **v4.9.4** du plugin.

## Générer le fichier `.mo`

Après avoir modifié `eventon-fr_FR.po`, compilez le fichier binaire nécessaire à WordPress avec :

```bash
msgfmt eventon-fr_FR.po -o eventon-fr_FR.mo
```

Placez ensuite `eventon-fr_FR.mo` dans `wp-content/languages/plugins` de votre installation WordPress.

## Contribuer

1. Forkez ce dépôt puis créez une branche dédiée à vos changements.
2. Mettez à jour `eventon-fr_FR.po` en conservant la cohérence terminologique.
3. Générez le fichier `.mo` comme indiqué ci-dessus.
4. Proposez une pull request en décrivant vos améliorations ou corrections.

Dernière mise à jour : 5 mai 2025.
