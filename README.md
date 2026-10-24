<!-- SPDX-License-Identifier: GPL-3.0-or-later -->
# MonDirect

*Français d'abord, English below.*

## Français

MonDirect est une application libre pour regarder les directs Twitch sur Android TV et sur téléphone. Ce dépôt ne
contient pas de code : seulement les versions publiées (APK, archive source, `update.json`, `proxy-catalog.json`,
`SHA256SUMS`), cette page, la licence et la politique de confidentialité.

### Installer sur une TV

1. Installe l'app **Downloader** (Play Store sur Google TV et Android TV, Amazon Appstore sur Fire TV).
2. Dans Downloader, saisis l'adresse **`mondirect.fr/tv`**.
3. Ou saisis le code Downloader (publié ici dès sa création).
4. En secours (site indisponible) :
   `https://github.com/LeRayo/MonDirect-releases/releases/latest/download/MonDirect.apk`

Ces adresses servent toujours la **dernière version stable**. Sur téléphone, ouvre la même adresse dans le navigateur.
Ensuite, MonDirect se met à jour depuis l'app (Réglages > Mises à jour) : les mises à jour viennent de ce dépôt et
sont refusées si leur signature diffère.

### Vérifier le fichier

Avant une **première** installation (aucune signature de référence sur l'appareil) :

- compare l'empreinte du fichier à la ligne de `SHA256SUMS` de la release : `sha256sum MonDirect.apk` ;
- vérifie l'empreinte SHA-256 du certificat de signature : `apksigner verify --print-certs MonDirect.apk` doit
  afficher l'empreinte publiée dans les notes de la première release.

`MonDirect.apk` est une copie octet pour octet de `mondirect-<version>.apk` (même ligne dans `SHA256SUMS`).

### Code source

MonDirect est un logiciel libre sous licence GPL-3.0-or-later (`LICENSE`). Chaque release porte son archive source
complète, `mondirect-<version>-source.tar.gz`, dans ses fichiers joints.

### Non-affiliation

MonDirect n'est ni affilié à Twitch, ni approuvé, ni sponsorisé par Twitch. Twitch est une marque de Twitch
Interactive, Inc. Confidentialité : `PRIVACY.md`.

## English

MonDirect is a free app to watch Twitch live streams on Android TV and phones. This repository contains no code: only
the published versions (APK, source archive, `update.json`, `proxy-catalog.json`, `SHA256SUMS`), this page, the license
and the privacy policy.

### Install on a TV

1. Install the **Downloader** app (Play Store on Google TV and Android TV, Amazon Appstore on Fire TV).
2. In Downloader, enter the address **`mondirect.fr/tv`**.
3. Or enter the Downloader code (published here once created).
4. Fallback (site unavailable):
   `https://github.com/LeRayo/MonDirect-releases/releases/latest/download/MonDirect.apk`

These addresses always serve the **latest stable version**. On a phone, open the same address in the browser. After
that, MonDirect updates itself from the app (Settings > Updates): updates come from this repository and are refused if
their signature differs.

### Verify the file

Before a **first** installation (the device has no reference signature yet):

- compare the file's hash with the release's `SHA256SUMS` line: `sha256sum MonDirect.apk`;
- check the SHA-256 fingerprint of the signing certificate: `apksigner verify --print-certs MonDirect.apk` must show
  the fingerprint published in the first release notes.

`MonDirect.apk` is a byte-for-byte copy of `mondirect-<version>.apk` (same line in `SHA256SUMS`).

### Source code

MonDirect is free software under the GPL-3.0-or-later (`LICENSE`). Every release carries its complete source archive,
`mondirect-<version>-source.tar.gz`, in its attached files.

### Not affiliated

MonDirect is not affiliated with, endorsed by or sponsored by Twitch. Twitch is a trademark of Twitch Interactive, Inc.
Privacy: `PRIVACY.md`.
