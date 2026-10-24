<!-- SPDX-License-Identifier: GPL-3.0-or-later -->
# Journal des versions / Changelog

*Français d'abord, English below.* Chaque version est publiée dans les
[releases](https://github.com/LeRayo/MonDirect-releases/releases) avec son APK, son archive source et `SHA256SUMS`.

## Français

### 0.1.1 — 2026-10-24

- Bloc « Soutenir MonDirect » dans Réglages > À propos : liens Buy Me a Coffee et PayPal (boutons sur téléphone, QR à
  scanner sur TV). Un don aide à payer le temps de développement, sans contrepartie : rien n'est réservé aux donateurs.
- TV : le tiroir de navigation distingue mieux la destination courante de l'entrée focalisée.
- Première mise à jour servie par l'app elle-même (Réglages > Mises à jour).

### 0.1.0 — 2026-10-24

Première version publique. MonDirect est un client Twitch libre (GPL-3.0-or-later) pour Android TV et téléphone : un
seul APK, deux interfaces.

**Regarder**

- Directs en qualité choisie, lecture audio seule, reprise de la lecture en arrière-plan avec notification (téléphone).
- Zapping entre les directs d'une liste (CH± et ←/→ sur TV, glissement sur téléphone) avec carte d'aperçu.
- Parcourir les chaînes pendant le direct (↑ sur TV, glissement vers le haut sur téléphone).
- Multivue : 2 flux sur TV et téléphone, jusqu'à 4 sur tablette.
- Vidéos à la demande avec chapitres, historique local des directs (« Regardés récemment »).
- Mini-lecteur sur téléphone.

**Suivre**

- Connexion au compte Twitch par code court saisi sur le téléphone ; regarder un direct reste possible sans compte.
- Favoris de chaînes et de catégories : rangées « Favoris en direct » et « Catégories favorites », épinglage dans les
  suivis, export et appairage vers la TV.
- Notifications « passe en direct » pour les favoris (téléphone) et bandeau au premier plan (TV).

**Chat**

- Chat en direct avec émotes et badges.
- Filtres : bots connus, ASCII art, mots, utilisateurs masqués ; chaînes masquées et filtre de titre.

**Personnaliser**

- Ordre des rangées de l'accueil et des boutons du lecteur, thème, raccourcis de la télécommande configurables (TV).
- Liste de proxys suggérés, jamais activée automatiquement.
- Mises à jour depuis l'application (Réglages > Mises à jour), refusées si la signature diffère.

Aucun compte MonDirect, aucune statistique envoyée, aucun serveur entre l'appareil et Twitch hormis un proxy ajouté
par l'utilisateur. Détails : `PRIVACY.md`.

## English

### 0.1.1 — 2026-10-24

- "Support MonDirect" block in Settings > About: Buy Me a Coffee and PayPal links (buttons on phone, QR code to scan on
  TV). A donation helps pay for development time, with nothing in return: no feature is reserved for donors.
- TV: the navigation drawer now tells the current destination apart from the focused entry.
- First update delivered by the app itself (Settings > Updates).

### 0.1.0 — 2026-10-24

First public release. MonDirect is a free Twitch client (GPL-3.0-or-later) for Android TV and phones: one APK, two
interfaces.

**Watch**

- Live streams at the chosen quality, audio-only playback, background playback with a notification (phone).
- Channel surfing through a list of live streams (CH± and ←/→ on TV, swipe on phone) with a preview card.
- Browse channels while watching (↑ on TV, swipe up on phone).
- Multiview: 2 streams on TV and phone, up to 4 on tablets.
- Videos on demand with chapters, local stream history ("Recently watched").
- Mini player on phone.

**Follow**

- Sign in to a Twitch account with a short code entered on the phone; watching a stream still works without an account.
- Favorite channels and categories: "Live favorites" and "Favorite categories" rows, pinned in followed channels, export
  and pairing to the TV.
- "Going live" notifications for favorites (phone) and a foreground banner (TV).

**Chat**

- Live chat with emotes and badges.
- Filters: known bots, ASCII art, words, hidden users; hidden channels and title filter.

**Customize**

- Order of home rows and player buttons, theme, configurable remote shortcuts (TV).
- Suggested proxy list, never enabled automatically.
- In-app updates (Settings > Updates), refused if the signature differs.

No MonDirect account, no statistics sent, no server between the device and Twitch except a proxy the user adds.
Details: `PRIVACY.md`.
