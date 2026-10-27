<!-- SPDX-License-Identifier: GPL-3.0-or-later -->
# Journal des versions / Changelog

*Français d'abord, English below.* Chaque version est publiée dans les
[releases](https://github.com/LeRayo/MonDirect-releases/releases) avec son APK, son archive source et `SHA256SUMS`.

## Français

### 0.1.3 — 2026-10-27

- Chaînes soutenues : par défaut, les proxys s'appliquent à toutes les chaînes. Un bouton « Soutenir », à côté de
  l'étoile des favoris sur la page de chaîne et dans le lecteur (téléphone et TV), ajoute une chaîne à la liste des
  chaînes soutenues : son direct est lu directement depuis Twitch, sans proxy ni contournement des coupures, pour que
  les publicités passent et que le créateur les touche. Un bandeau le rappelle au lancement de la lecture.
- La liste se gère dans Réglages > Proxys > Chaînes soutenues (retirer une chaîne, tout retirer). Elle est exportée,
  importée et appairée vers la TV comme les favoris.
- La fonction se coupe dans Personnalisation ; sur TV, un raccourci de télécommande peut soutenir ou ne plus soutenir
  la chaîne en cours.

### 0.1.2 — 2026-10-26

- Le compte Twitch devient facultatif : « Continuer sans compte » sur l'écran de connexion. Directs populaires,
  catégories, recherche, pages de chaîne, directs, rediffusions, clips et lecture du chat fonctionnent sans se connecter ;
  le choix est mémorisé.
- Là où le compte reste nécessaire (chaînes suivies, suivre une chaîne, écrire dans le chat, alertes), une invite
  « Connexion » prend la place de la fonction.
- Sans compte, le catalogue vient de l'interface web de Twitch : une seule page par liste (30 directs, 100 catégories,
  rediffusions ou clips) et pas de badges dans le chat. Avec un compte, rien ne change.
- L'introduction au premier lancement explique ce qui marche avec ou sans compte.

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

### 0.1.3 — 2026-10-27

- Supported channels: by default, proxies apply to every channel. A "Support" button, next to the favourite star on
  the channel page and in the player (phone and TV), adds a channel to the supported list: its stream is played
  straight from Twitch, with no proxy and no outage workaround, so ads play and the creator gets them. A banner
  reminds you when playback starts.
- The list is managed in Settings > Proxies > Supported channels (remove one channel, remove all). It is exported,
  imported and paired to the TV like favourites.
- The feature can be turned off in Customisation; on TV, a remote shortcut can support or stop supporting the current
  channel.

### 0.1.2 — 2026-10-26

- The Twitch account is now optional: "Continue without an account" on the sign-in screen. Popular streams,
  categories, search, channel pages, streams, videos, clips and reading chat all work without signing in; the choice is
  remembered.
- Where an account is still required (followed channels, following a channel, writing in chat, alerts), a "Sign in"
  prompt takes the feature's place.
- Without an account, the catalogue comes from Twitch's web interface: a single page per list (30 streams, 100
  categories, videos or clips) and no badges in chat. With an account, nothing changes.
- The first-launch introduction explains what works with and without an account.

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
