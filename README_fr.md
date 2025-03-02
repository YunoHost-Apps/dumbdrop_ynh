<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# DumbDrop pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dumbdrop)](https://ci-apps.yunohost.org/ci/apps/dumbdrop/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dumbdrop)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dumbdrop)

[![Installer DumbDrop avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdrop)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer DumbDrop rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Une application simple et stupide de téléchargement de fichiers qui fournit une interface propre et moderne pour glisser et déposer des fichiers. Construite avec Node.js et du JavaScript vanille.

### Caractéristiques

- Téléchargement de fichiers par glisser-déposer
- Sélection de plusieurs fichiers
- Interface utilisateur propre et réactive avec mode sombre
- Prise en charge de Docker avec configuration facile
- Prise en charge du téléchargement de répertoire (maintien de la structure)
- Protection par code PIN en option
- Interface conviviale pour les mobiles
- Notifications configurables via Apprise
- Aucune dépendance côté client
- Fonctions de sécurité intégrées
- Limites de taille de fichier configurables
- Filtrage des extensions de fichiers
    

**Version incluse :** 2025.02.27~ynh1

## Captures d’écran

![Capture d’écran de DumbDrop](./doc/screenshots/screeshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.dumbware.io/>
- Dépôt de code officiel de l’app : <https://github.com/DumbWareio/DumbDrop>
- YunoHost Store : <https://apps.yunohost.org/app/dumbdrop>
- Signaler un bug : <https://github.com/YunoHost-Apps/dumbdrop_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dumbdrop -u https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
