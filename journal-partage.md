# Journal de travail

_Simon Van de Meersche · généré le mercredi 21 octobre 2026 à 23:56_

> Version partagée : les notes personnelles ne sont pas incluses.

## mercredi 21 octobre 2026

**1 commit et 1 tâche sur 2 projets.**

### Momentum

- **1 commit** · `momentum`
  - Tâches : sidebar zones/projets façon Things 3 · `5e1eeaf`

### Elevedia — agents vocaux

- **Tâche** · Agent vocal : transfert d'appel, mise en mute et SMS de confirmation — Spécifications issues de la note du jour : transfert de l'agent vers le portable du restaurateur, mise en mute pour écouter la conversation, et SMS de confirmation au client.

---

## mardi 20 octobre 2026

**7 commits sur 3 projets.**

### Momentum

- **3 commits** · `momentum`
  - Omarchy : la palette suit les bascules de thème · `a13e964`
  - Momentum : archiver et supprimer les zones et projets · `e7022f7`
  - Momentum : actions au survol et gestion des zones et projets · `17472be`

### Mail Hub

- **3 commits** · `mail-hub`
  - triage: classement déterministe via MCP, relances et timer · `741b21b`
  - triage: étoile sécurité, état des fils gardés, libellé En attente sur les relances · `1c7ae28`
  - triage: règles decodo et webinaires · `0f90d32`

### Mailspring

- **1 commit** · `mailspring-mailhub`
  - mcp: add create_category (Gmail labels / Outlook folders) · `2ef9708`

---

## lundi 19 octobre 2026

**5 commits sur 3 projets.**

### Momentum

- **3 commits** · `momentum`
  - HUD : supprimer une tâche depuis la modal ne la coche plus · `03235cc`
  - HUD : le clic montre les tâches, avec sous-tâches et lecteur d'ambiance · `f267a3b`
  - Docs : le clic de la pastille ouvre les tâches, plus l'ambiance · `3a9015f`

### Mailspring

- **1 commit** · `mailspring-mailhub`
  - Mail Hub: notification policy fed by mail-hub + personnalisation du fork · `5ae073f`

### Mail Hub

- **1 commit** · `mail-hub`
  - API locale pour l'UI + unité systemd mail-hub-server · `0cddd5d`

---

## dimanche 18 octobre 2026

**4 commits.**

### Momentum

- **4 commits** · `momentum`
  - Ambiances sonores : la musique du focus, tes fichiers en boucle · `47f238d`
  - Réglages : choisir son ambiance dans le tableau de bord · `1cf048f`
  - HUD : la pastille ne s'anime que si elle est visible et qu'un focus tourne · `0ee810e`
  - HUD : la pastille ne redessine plus en boucle au repos · `390a101`

---

## samedi 17 octobre 2026

**11 commits sur 2 projets.**

### Momentum

- **7 commits** · `momentum`
  - v0.5 : page OKR repensée, HUD de focus interactif · `d9da666`
  - v0.6 : réglages dans l'app (roue ⚙) et fermeture au clic extérieur · `80694ba`
  - v0.7 : focus libre, menu des tâches, pastille invocable et multi-écrans · `4c37915`
  - HUD : le clic extérieur referme vraiment la modal et le menu · `9c43420`
  - HUD : un voile sur les autres ecrans ne recoit rien, on passe par le focus · `15153e0`
  - Page OKR : un cercle qui se remplit au lieu des barres · `b89669b`
  - Chronos : le temps est publie a la seconde, plus par pas de 6 s · `27ca0ab`

### Talkify

- **4 commits** · `talkify-omarchy`
  - [fix(vocab): fold accents to ASCII before the phonetic keys](https://github.com/InsaneArts/talkify-omarchy/commit/d9bc27226a74dd60b5bd70460b1237c4bbd7ad0d) · `d9bc272`
  - [feat(trigger): a toggle mode, and no click can cancel a dictation](https://github.com/InsaneArts/talkify-omarchy/commit/21d838c6f8a4b7260f267372e05e126e3d947cdb) · `21d838c`
  - [feat(trigger): say which mode the daemon starts with](https://github.com/InsaneArts/talkify-omarchy/commit/06cf92e75336df29262ff974b31113203a6c73b9) · `06cf92e`
  - [fix(trigger): a toggle trigger keeps its mode across sessions](https://github.com/InsaneArts/talkify-omarchy/commit/18c01d2cdb250b7a3cd871d0d6fda69f208dee30) · `18c01d2`

---

## vendredi 16 octobre 2026

**5 commits.**

### Momentum

- **5 commits** · `momentum`
  - Momentum : moteur de momentum natif Omarchy · `261c294`
  - v0.2 : tableau de bord complet, habitudes, OKR, revues, XP et quêtes · `73db7f5`
  - Sons arcade et animations de palier (v0.3) · `8ff8f4b`
  - Fx : les sons d'interface ne dépendent plus des animations · `2419bda`
  - v0.4 : sous-tâches validables, HUD de focus, anneau animé dans la barre · `bf09123`

---

## mardi 22 septembre 2026

**11 commits.**

### Mnemosyne

- **11 commits** · `mnemosyne`
  - Baseline: Mnemosyne 0.1.0 avant pivot conseiller d'automatisation · `ca3eef1`
  - Conseiller d'automatisation : moteur en graphes, épisodes, routines, fiches sourcées, reviews · `77807dc`
  - Vue Conseiller, réglages, témoin discret, guide et README honnêtes · `13a0ceb`
  - Grille goulot : postures, décisions délégables, clé OpenCode réutilisée, secrets chiffrés · `933455b`
  - Réglage mesuré sur données réelles : raisonnement coupé pour les épisodes, postures précisées · `e46f570`
  - Installateur 0.2.0 construit sous le Node d'Electron, sans Node 22 système · `afa0e86`
  - Lab note : raisonnement du modèle et tests hermétiques · `cb8538a`
  - Capteur sans fenêtre et lecture par l'API de Screenpipe · `b2d2fd8`
  - Contexte vivant : mémoire apprise, notes, agents (Orca, sessions Claude), serveurs SSH · `e1998ed`
  - Faits rédigés sans pronom ; version 0.3.0 · `b812f6f`
  - Lab note : capteur sous Windows et accès Screenpipe · `feb6784`

---
