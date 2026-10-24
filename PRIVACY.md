<!-- SPDX-License-Identifier: GPL-3.0-or-later -->
# Politique de confidentialité / Privacy policy

*Français d'abord, English below.*

## Français

MonDirect est un client Twitch non officiel pour Android TV et téléphone. Il n'est ni affilié, ni approuvé, ni sponsorisé
par Twitch Interactive, Inc. Cette page dit ce que l'application fait des données, en peu de mots.

### Ce que MonDirect ne fait pas

- Aucun outil de statistiques, de mesure d'audience, de publicité ou de pistage. Aucun identifiant publicitaire.
- Aucun service de remontée de plantages : les rapports de plantage restent sur l'appareil (voir plus bas).
- Aucun compte MonDirect et aucun serveur MonDirect : l'application n'envoie rien à son auteur.

### Ce qui est enregistré sur l'appareil

- **Réglages et préférences** (thème, langue, rangées de l'accueil, proxys que vous ajoutez, historique de recherche).
  Ils sont exclus de l'export de réglages quand c'est sensible (historique de recherche), et vous pouvez les effacer
  depuis les réglages d'Android (Stockage, Effacer les données).
- **Session Twitch** (jetons de connexion), si vous vous connectez. Elle est chiffrée avec une clé de l'Android Keystore.
  Si l'appareil n'a pas de Keystore utilisable, elle reste en mémoire et la connexion est redemandée à chaque lancement,
  sauf si vous choisissez explicitement « Rester connecté quand même » (la session est alors enregistrée sans chiffrement).
  Les jetons sont exclus des sauvegardes Android.
- **Compte de lecture web** (jeton lié au site de Twitch), si vous le liez vous-même. Il n'est jamais envoyé qu'aux
  services de Twitch.
- **Rapports de plantage locaux** (réglage « Confidentialité », activé par défaut) : un fichier texte (date, version,
  modèle d'appareil, version d'Android, trace). Les jetons, cookies, Client-ID, URL de proxy complètes et contenus de chat
  en sont retirés avant écriture. Le rapport ne quitte l'appareil que si **vous** le partagez. Vous pouvez le consulter, le
  supprimer, ou désactiver l'enregistrement.

### Historique local

Ce que vous regardez reste **sur l'appareil seulement** : jamais envoyé à l'auteur, jamais inclus dans l'export des
réglages, jamais transféré par l'appairage, exclu des sauvegardes Android.

- **Directs regardés** : les 100 dernières chaînes regardées au moins 20 secondes (identifiant, nom, date du dernier
  visionnage ; ni titre, ni catégorie, ni image). Ils servent à la rangée « Regardés récemment ». Effaçables dans
  Réglages > Confidentialité (une chaîne ou tout l'historique), ou avec « Effacer les données de cette fonction »
  (Réglages > Personnalisation, fonction « Historique des directs »). Couper la fonction arrête l'enregistrement sans
  effacer l'historique.
- **Positions de reprise des vidéos** (rediffusions et VOD) : où vous vous êtes arrêté. Effaçables dans
  Réglages > Confidentialité, « Effacer l'historique de visionnage ».
- **État des alertes « en direct »** : les directs déjà signalés, pour ne pas vous prévenir deux fois. Effacé avec
  « Effacer les données de cette fonction » (Personnalisation, fonction « Notifications « en direct » ») ou en changeant
  de compte.

### Services contactés

- **Twitch** (connexion, flux vidéo, liste des chaînes, chat), avec vos jetons si vous êtes connecté. Les conditions et la
  politique de confidentialité de Twitch s'appliquent à ces échanges.
- **BetterTTV, FrankerFaceZ et 7TV**, pour les émotes tierces, désactivables dans les réglages du chat.
- **Notifications « passe en direct »** (désactivées par défaut, Réglages > Notifications) : seulement si vous les
  activez et êtes connecté, MonDirect demande à Twitch (API Helix, avec vos jetons) quelles chaînes favorites (ou
  suivies, selon votre choix) sont en direct : toutes les 3 minutes quand l'application est ouverte, et sur téléphone
  environ toutes les 15 minutes en arrière-plan (WorkManager d'Android, sans service Google). Aucune donnée ne quitte
  l'appareil vers un autre service ; sur TV, rien n'est vérifié quand l'application est fermée.
- **Vos proxys HLS**, si vous en configurez : ce sont des services tiers que vous choisissez. MonDirect ne leur envoie ni
  jeton, ni cookie, ni Client-ID, mais ils voient l'adresse IP de l'appareil et la chaîne demandée.
- **GitHub** (dépôt public de releases), uniquement si cette version de MonDirect inclut les mises à jour intégrées :
  vérification au plus une fois par 24 h, sans authentification, et téléchargement d'une mise à jour uniquement sur votre
  demande. Les versions sans dépôt public n'en contactent aucun.
- **GitHub, pour la liste de proxys** (même dépôt public de releases) : seulement quand **vous** appuyez sur
  « Actualiser la liste » dans « Choisir dans la liste » (jamais au lancement ni en arrière-plan), une requête sans
  authentification télécharge la liste de proxys suggérés de la dernière version stable. Elle est gardée sur l'appareil,
  hors des sauvegardes et de l'export ; rien n'est ajouté ni activé sans votre « Ajouter ».

### Code source et contact

MonDirect est un logiciel libre (GPL-3.0-or-later). Le code source correspondant accompagne chaque APK distribué.
Pour une question sur cette politique, utilisez les tickets du dépôt public de releases, s'il existe.

## English

MonDirect is an unofficial Twitch client for Android TV and phones. It is not affiliated with, endorsed by or sponsored by
Twitch Interactive, Inc. This page explains, briefly, what the app does with data.

### What MonDirect does not do

- No analytics, audience measurement, advertising or tracking tools. No advertising identifier.
- No crash reporting service: crash reports stay on the device (see below).
- No MonDirect account and no MonDirect server: the app sends nothing to its author.

### What is stored on the device

- **Settings and preferences** (theme, language, home rows, proxies you add, search history). Sensitive items (search
  history) are left out of the settings export, and you can erase everything from Android's settings (Storage, Clear data).
- **Twitch session** (sign-in tokens), if you sign in. It is encrypted with a key from the Android Keystore. If the device
  has no usable Keystore, it stays in memory and sign-in is asked again at each launch, unless you explicitly choose
  "Stay signed in anyway" (the session is then stored unencrypted). Tokens are excluded from Android backups.
- **Web playback account** (a token tied to Twitch's website), only if you link it yourself. It is only ever sent to
  Twitch services.
- **Local crash reports** ("Privacy" setting, on by default): a text file (date, version, device model, Android version,
  stack trace). Tokens, cookies, Client-IDs, full proxy URLs and chat content are removed before writing. The report
  leaves the device only if **you** share it. You can read it, delete it, or turn recording off.

### Local history

What you watch stays **on the device only**: never sent to the author, never included in the settings export, never
transferred by pairing, excluded from Android backups.

- **Watched live streams**: the last 100 channels watched for at least 20 seconds (identifier, name, date last watched;
  no title, category or image). They feed the "Recently watched" row. You can clear them in Settings > Privacy (one
  channel or the whole history), or with "Clear this feature's data" (Settings > Customization, "Live history"
  feature). Turning the feature off stops recording without clearing the history.
- **Video resume positions** (past broadcasts and VODs): where you stopped. You can clear them in Settings > Privacy,
  "Clear watch history".
- **"Live" alert state**: streams already announced, so you are not told twice. Cleared with "Clear this feature's
  data" (Customization, "“Live” notifications" feature) or when you change account.

### Services contacted

- **Twitch** (sign-in, video streams, channel lists, chat), with your tokens if you are signed in. Twitch's terms and
  privacy policy apply to these exchanges.
- **BetterTTV, FrankerFaceZ and 7TV**, for third-party emotes, which you can turn off in the chat settings.
- **"Goes live" notifications** (off by default, Settings > Notifications): only if you turn them on and are signed in,
  MonDirect asks Twitch (Helix API, with your tokens) which favorite (or followed, as you choose) channels are live:
  every 3 minutes while the app is open, and on phones about every 15 minutes in the background (Android's WorkManager,
  no Google services). No data leaves the device for any other service; on TV, nothing is checked while the app is
  closed.
- **Your HLS proxies**, if you configure any: they are third-party services you choose. MonDirect sends them no token,
  cookie or Client-ID, but they see the device's IP address and the requested channel.
- **GitHub** (public releases repository), only if this build of MonDirect includes in-app updates: a check at most once
  every 24 hours, unauthenticated, and an update is downloaded only when you ask. Builds without a public repository
  contact none.
- **GitHub, for the proxy list** (same public releases repository): only when **you** tap "Refresh the list" in "Choose
  from the list" (never at launch or in the background), an unauthenticated request downloads the suggested proxy list
  of the latest stable version. It is kept on the device, out of backups and exports; nothing is added or turned on
  without your "Add".

### Source code and contact

MonDirect is free software (GPL-3.0-or-later). The corresponding source code comes with every distributed APK. For a
question about this policy, use the issues of the public releases repository, if there is one.
