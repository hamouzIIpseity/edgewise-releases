# Edgewise

*Install guide for Edgewise, an Android app that lights the screen edge on notifications. French below.*


Edgewise allume le bord de l'écran quand une notification arrive, dans la couleur de l'app, et
ajoute des zones tactiles invisibles sur le bord. Il ne vient pas du Play Store : on installe le
fichier APK à la main. Comptez cinq minutes.

**Vie privée** : Edgewise n'a pas accès à Internet (Android ne lui donne pas cette autorisation),
n'a ni compte, ni pub, ni traqueur. Il lit vos notifications pour les afficher, et rien ne quitte
le téléphone.

## 1. Télécharger

Sur le téléphone, ouvrez **[la dernière version](https://github.com/hamouzIIpseity/edgewise-releases/releases/latest)** et téléchargez le fichier
`edgewise-<version>.apk` (rubrique « Assets »).

## 2. Installer

1. Ouvrez le fichier téléchargé (notification du navigateur, ou appli Fichiers › Téléchargements).
2. Android demande d'autoriser l'installation depuis cette source : touchez **Paramètres**,
   activez **Autoriser depuis cette source**, puis revenez.
3. Si Play Protect avertit d'une appli inconnue : **Plus de détails › Installer quand même**.
   C'est normal pour une appli hors Play Store.

## 3. Mise en route

Ouvrez Edgewise : la carte **Mise en route** de l'Accueil vous guide pas à pas.

- **Accès aux notifications** et **service d'accessibilité** : Edgewise en a besoin pour lire les
  notifications et dessiner sur le bord de l'écran.
- **Interrupteur grisé** (Android 13 et plus, normal pour une appli installée à la main) :
  Paramètres › Applis › Edgewise › **⋮** (en haut à droite) › **Autoriser les paramètres
  restreints**, puis revenez activer l'interrupteur.
- **Batterie sans restriction**, sinon le téléphone peut couper Edgewise au bout d'un moment :
  - Samsung : Paramètres › Applis › Edgewise › Batterie › Non restreinte.
  - Xiaomi : Paramètres › Applis › Edgewise : Démarrage auto activé, Économiseur de batterie sur
    Pas de restrictions.
  - Pixel : Paramètres › Applis › Edgewise › Batterie › Sans restriction.
  - Autres : Paramètres › Applis › Edgewise › Batterie : sans restriction.

Ensuite, **Tester** sur l'Accueil envoie une notification d'essai.

## Mettre à jour

Téléchargez le nouvel APK depuis [la dernière version](https://github.com/hamouzIIpseity/edgewise-releases/releases/latest) et installez-le par-dessus : vos
réglages restent. Pour être prévenu tout seul : l'appli [Obtainium](https://obtainium.imranr.dev)
suit cette page (ajoutez l'adresse `https://github.com/hamouzIIpseity/edgewise-releases`). Si Android refuse
(« conflit avec un paquet existant »), prévenez-moi avant de désinstaller : désinstaller efface
les réglages, sauf si vous les avez exportés (Accueil › ⋮ › Exporter).

Après une mise à jour, certains téléphones coupent le service d'accessibilité : si les lueurs ne
s'allument plus, réactivez-le depuis la Mise en route.

## Quelque chose ne marche pas

Accueil › **⋮** › **Copier le diagnostic**, puis collez-le dans un message à la personne qui vous a
invité, avec ce que vous faisiez. Le diagnostic contient le modèle du téléphone, la version
d'Android et d'Edgewise et le journal de l'app, jamais le contenu de vos notifications.

## Désinstaller

**D'abord**, si vous avez activé « Masquer les bannières » : coupez-le dans Edgewise (ou déliez
l'appareil associé). Sinon les apps qui avaient une lueur restent sans bannière après la
désinstallation, et il faut les remettre une par une dans leurs réglages de notification.

Ensuite : Paramètres › Applis › Edgewise › Désinstaller.
