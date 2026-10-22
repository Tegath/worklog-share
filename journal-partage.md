# Journal de travail

_Simon Van de Meersche · généré le jeudi 22 octobre 2026 à 12:54_

> Version partagée : les notes personnelles ne sont pas incluses.

## Résumé pour associés

- **Elevedia** — Cockpit client unifié pour les verticales, avec une configuration vocale canonique.
- **Elevedia** — Parcours d'activation fiabilisé : checklist, parité des agents et garde-fous sur les essais.
- **Elevedia** — Self-service immobilier : essai sans carte, abonnement, activation et attribution du numéro.
- **Elevedia** — Sécurité renforcée : rôles admin, isolation des données et limites anti-abus sur les formulaires publics.
- **Multichannel** — Inbox email fiabilisée : nos propres messages ne sont plus ingérés comme des réponses prospects.
- **Hashtag** — Nouveau backend SEO avec rotation automatique des clés.
- **Momentum** — Interface de focus interactive, gestion des zones/projets et ambiances sonores.
- **Momentum OS** — Dossiers Google Drive reliés aux zones, import de documents en tâches et copie en une tâche.
- **Mail Hub** — Triage email automatique, relances et API locale pour l'interface.
- **Mailspring** — Politique de notification et catégories Gmail/Outlook.
- **Talkify** — Dictée vocale avec mode toggle, démarrage explicite et clés phonétiques insensibles aux accents.
- **Mnemosyne** — Conseiller d'automatisation (routines, fiches sourcées, installateur 0.2).
- **Ideta** — Moteur d'IA hybride local/cloud, avec repli automatique entre les deux.
- **Ops** — Studio vidéo (formats, voix, musique) et infrastructure/Mission Control consolidés.

## mercredi 21 octobre 2026

**4 PR fusionnées · 5 PR ouvertes · 1 tâche**

### Elevedia — agents vocaux

- **PR fusionnée** · [Client cockpit with canonical voice config (all five verticals)](https://github.com/Tegath/elevedia/pull/679)
- **PR fusionnée** · [Install app-conductor in the dashboard Docker deps stage](https://github.com/Tegath/elevedia/pull/680)
- **PR fusionnée** · [Dependency-aware setup checklist on all agent pages](https://github.com/Tegath/elevedia/pull/681)
- **Tâche** · Agent vocal : transfert d'appel, mise en mute et SMS de confirmation — Spécifications issues de la note du jour : transfert de l'agent vers le portable du restaurateur, mise en mute pour écouter la conversation, et SMS de confirmation au client.
- **PR ouverte** · [Unify the client chat with the guided funnel](https://github.com/Tegath/elevedia/pull/682)
- **PR fusionnée** · [Unify the client chat with the guided funnel](https://github.com/Tegath/elevedia/pull/683)

---

## mardi 20 octobre 2026

**2 PR fusionnées · 2 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · [Hallucinations Whisper, étapes explicites, opportunité manquante](https://github.com/Tegath/elevedia/pull/677)
- **PR fusionnée** · [Pas de match par préfixe sur un nom à un seul mot](https://github.com/Tegath/elevedia/pull/678)

---

## lundi 19 octobre 2026

**8 PR fusionnées · 9 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · [Plus de fausses répétitions dans les transcriptions d'appel](https://github.com/Tegath/elevedia/pull/668)
- **PR fusionnée** · [Journal vocal — dicter une interaction sans formulaire](https://github.com/Tegath/elevedia/pull/669)
- **PR fusionnée** · [Laisser /api/voice-log atteindre son auth token](https://github.com/Tegath/elevedia/pull/670)
- **PR fusionnée** · [Extraction vocale sur Gemma-4 local (Anthropic HS)](https://github.com/Tegath/elevedia/pull/671)
- **PR fusionnée** · [Schéma vocal tolérant (nulls Gemma-4) + Groq gpt-oss-120b](https://github.com/Tegath/elevedia/pull/672)
- **PR fusionnée** · [L'annulation vocal supprime aussi l'établissement créé](https://github.com/Tegath/elevedia/pull/673)
- **PR fusionnée** · [Normalise la raison de perte avant l'enum Postgres](https://github.com/Tegath/elevedia/pull/674)
- **PR fusionnée** · [Résolveur vocal — pas de match sur un token générique court](https://github.com/Tegath/elevedia/pull/675)
- **PR fusionnée** · [Groq chat opt-in + erreur LLM lisible](https://github.com/Tegath/elevedia/pull/676)

---

## dimanche 18 octobre 2026

**3 PR fusionnées**

### Elevedia — agents vocaux

- **PR fusionnée** · [Un seul SMS par annulation de série](https://github.com/Tegath/elevedia/pull/664)
- **PR fusionnée** · [Rappel de visite H-2 coupable par agence (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/661)
- **PR fusionnée** · [Book-visit enregistre la date de naissance du visiteur (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/662)

---

## samedi 17 octobre 2026

**1 PR ouverte**

### Elevedia — agents vocaux

- **PR ouverte** · [Portage de numéro en self-service (resto) — parcours client, file admin, relances](https://github.com/Tegath/elevedia/pull/667)

---

## vendredi 16 octobre 2026

**2 PR fusionnées · 3 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · [Un seul SMS par annulation de série](https://github.com/Tegath/elevedia/pull/664)
- **PR fusionnée** · [Fenêtres par prestation, RDV chaînés multi-collaborateurs, droits staff, timeline](https://github.com/Tegath/elevedia/pull/665)
- **PR fusionnée** · [Statut de ship du patch moteur médecins (e797e9d, LIVRÉ)](https://github.com/Tegath/elevedia/pull/666)

---

## mercredi 14 octobre 2026

**3 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · [Rappel de visite H-2 coupable par agence (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/661)
- **PR ouverte** · [Book-visit enregistre la date de naissance du visiteur (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/662)
- **PR ouverte** · [Golden v1.9 — adresse à l'annonce, date de naissance, confirmation du numéro (cahier IDR)](https://github.com/Tegath/elevedia/pull/663)

---

## jeudi 1 octobre 2026

**8 PR fusionnées · 8 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · [Dashboard P1 — tickets de table, clients, appels](https://github.com/Tegath/elevedia/pull/653)
- **PR fusionnée** · [Réglages resto — les choix client pilotent le flow golden (v2)](https://github.com/Tegath/elevedia/pull/654)
- **PR fusionnée** · [Liste d'attente gatée par la clé catalogue medecins.waitlist.enabled](https://github.com/Tegath/elevedia/pull/655)
- **PR fusionnée** · [L'assistant self-serve du restaurateur — chat d'abord, garde-fous intacts](https://github.com/Tegath/elevedia/pull/656)
- **PR fusionnée** · [Consignes pré-examen par acte (CIM² v1)](https://github.com/Tegath/elevedia/pull/657)
- **PR fusionnée** · [Appointments.prestation_id — le RDV porte l'acte (consignes voix)](https://github.com/Tegath/elevedia/pull/658)
- **PR fusionnée** · [Capacités bornées, prompt client, verdict du run + montage services](https://github.com/Tegath/elevedia/pull/659)
- **PR fusionnée** · [Médecins + notaire montés (même coquille)](https://github.com/Tegath/elevedia/pull/660)

---

## mercredi 30 septembre 2026

**4 PR fusionnées · 5 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · [Registry(diagrammes): specs flux-appel (gabarit schémas tldraw)](https://github.com/Tegath/kb/pull/1)
- **PR fusionnée** · [SSI-4 — onboarding immo : étape formule + reprise au bon endroit](https://github.com/Tegath/elevedia/pull/649)
- **PR fusionnée** · [KDS Baba P1 : n° de table figé + passe bar « Plat prêt » + alertes par poste](https://github.com/Tegath/elevedia/pull/650)
- **PR fusionnée** · [Dashboards clients depuis demo.elevedia.be sans accès admin](https://github.com/Tegath/elevedia/pull/651)
- **PR fusionnée** · [Resto births get their public booking_slug](https://github.com/Tegath/elevedia/pull/652)

---

## mardi 29 septembre 2026

**10 PR fusionnées · 10 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · [Clonage de voix + cartes voix sur la page agent (alignement phase A)](https://github.com/Tegath/elevedia/pull/639)
- **PR fusionnée** · [Page agent alignée sur les 4 autres verticales (phase B)](https://github.com/Tegath/elevedia/pull/641)
- **PR fusionnée** · [Dashboard: marquer les tours agent non prononcés (transcription)](https://github.com/Tegath/elevedia/pull/642)
- **PR fusionnée** · [Passer full_name au createUser — la naissance médecins mourait à l'étape 1](https://github.com/Tegath/elevedia/pull/644)
- **PR fusionnée** · [Parité — colonne notifications, schéma Drizzle, garde naissance (phase C)](https://github.com/Tegath/elevedia/pull/643)
- **PR fusionnée** · [SSI-1 (v1) — essai sans carte : cap des appels test + un essai par téléphone](https://github.com/Tegath/elevedia/pull/640)
- **PR fusionnée** · [Ops(birth): banc de naissance médecins versionné (smoke dev)](https://github.com/Tegath/elevedia/pull/646)
- **PR fusionnée** · [SSI-2 — checkout abonnement immo → activation automatique](https://github.com/Tegath/elevedia/pull/645)
- **PR fusionnée** · [La recette bloquante ne se mettait plus en file depuis le 26-09](https://github.com/Tegath/elevedia/pull/647)
- **PR fusionnée** · [SSI-3 (immo) — une seule source de prix + portail self-service](https://github.com/Tegath/elevedia/pull/648)

---

## lundi 28 septembre 2026

**2 PR fusionnées · 2 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · [Clonage de voix client via Gradium (4 dashboards)](https://github.com/Tegath/elevedia/pull/638)
- **PR fusionnée** · [SSI-0 (D2) — le DID se claim à l'activation, plus à la naissance](https://github.com/Tegath/elevedia/pull/637)

---

## dimanche 27 septembre 2026

**1 PR fusionnée · 1 PR ouverte**

### Elevedia — agents vocaux

- **PR fusionnée** · [Duplex_resume + registre de comportement — les naissances héritent de tous les fixes](https://github.com/Tegath/elevedia/pull/636)

---

## samedi 26 septembre 2026

**4 PR fusionnées · 6 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · [Quota atteint = surconsommation comptée, jamais de pause](https://github.com/Tegath/elevedia/pull/630)
- **PR fusionnée** · [La migration quota-overage cible consume_minutes (pas consume_new_call_minutes)](https://github.com/Tegath/elevedia/pull/631)
- **PR fusionnée** · [Quota atteint = surconsommation comptée, jamais de pause](https://github.com/Tegath/elevedia/pull/632)
- **PR ouverte** · [Une relance sur 5xx/timeout — la confirmation ne part plus en fumée](https://github.com/Tegath/elevedia/pull/633)
- **PR ouverte** · [Le juge LLM en 2e ligne de la fiche agent](https://github.com/Tegath/elevedia/pull/634)
- **PR fusionnée** · [Parité de la page /agent avec le client resto](https://github.com/Tegath/elevedia/pull/635)

---

## vendredi 25 septembre 2026

**6 PR fusionnées · 6 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · [Résa invité sans compte sur le site public](https://github.com/Tegath/elevedia/pull/624)
- **PR fusionnée** · [Parité admin Imovia ↔ Elevedia : agences, analytics, rapports, usage](https://github.com/Tegath/elevedia/pull/625)
- **PR fusionnée** · [Admin Imovia : page Agents vocaux (liste + fiche agent canonique)](https://github.com/Tegath/elevedia/pull/626)
- **PR fusionnée** · [Admin Imovia — vérif agents : bug sync numéros, numéro assignable, horaires d'ouverture](https://github.com/Tegath/elevedia/pull/627)
- **PR fusionnée** · [Admin Imovia — garde-fou numéros : le pool ne peut plus voler un numéro d'une autre verticale](https://github.com/Tegath/elevedia/pull/628)
- **PR fusionnée** · [HOTFIX — garde-fou pool : basé sur le trunk LiveKit, pas la connexion Telnyx](https://github.com/Tegath/elevedia/pull/629)

---

## jeudi 24 septembre 2026

**2 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · [Variable {{outil}} dans l'outreach (plateforme métier détectée)](https://github.com/Tegath/elevedia/pull/622)
- **PR ouverte** · [Crm_directory_plateformes — plateformes métier des fiches (détection, annuaires, file)](https://github.com/Tegath/elevedia/pull/623)

---

## mercredi 23 septembre 2026

**13 PR fusionnées · 14 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · [Security(db): lock down users, definer functions, RLS (migrations NOT applied)](https://github.com/Tegath/elevedia/pull/610)
- **PR fusionnée** · [Security: lock admin server actions + app_metadata role checks](https://github.com/Tegath/elevedia/pull/612)
- **PR fusionnée** · [Security: backend fixes (Mollie, SMS pumping, SSRF, IDOR, fail-closed crons)](https://github.com/Tegath/elevedia/pull/611)
- **PR fusionnée** · [Security(crm): app_metadata roles + ownership checks](https://github.com/Tegath/elevedia/pull/609)
- **PR fusionnée** · [Security: OAuth callbacks, immo roles, fail-closed crons, tenant filters](https://github.com/Tegath/elevedia/pull/613)
- **PR fusionnée** · [Public booking limits, customer no-overwrite, server-proven onboarding phone](https://github.com/Tegath/elevedia/pull/614)
- **PR fusionnée** · [Dashboard: touch-first pass (tablette, doigts, mots simples)](https://github.com/Tegath/elevedia/pull/615)
- **PR fusionnée** · [Nouveaux agents nés avec la voix Cartesia Inès](https://github.com/Tegath/elevedia/pull/616)
- **PR fusionnée** · [Cap anonymous order creation (anti SMS/email/kitchen abuse)](https://github.com/Tegath/elevedia/pull/617)
- **PR fusionnée** · [Sec: CRM gcal OAuth state signing, .env ignore, sharp 0.35.4](https://github.com/Tegath/elevedia/pull/618)
- **PR fusionnée** · [Close birth parity gaps (immo admin wizard, notaire golden, fr+nl, demos)](https://github.com/Tegath/elevedia/pull/619)
- **PR fusionnée** · [Sec: invisible anti-bot guard on public forms + medecins signup limits](https://github.com/Tegath/elevedia/pull/620)
- **PR fusionnée** · [Cartesia credit tracking + premium-voice fallback alert](https://github.com/Tegath/elevedia/pull/621)

### Multichannel — outreach

- **PR fusionnée** · [Never ingest our own mail as a prospect reply](https://github.com/Tegath/layton-multichannel/pull/10)

---

## Répertoire

- **Elevedia** (produit) — Agents vocaux IA pour six verticales : resto, immo, médecins, dentistes, coiffeurs et notaires. · alias : agents vocaux, voix
- **Imovia** (client) — Client immobilier — base, dashboard admin et agents vocaux. · alias : Immo
- **IDR** (client) — Client immobilier — cahier des charges, visites et rappels. · alias : cahier IDR
- **Baba** (client) — Client restaurant — agent vocal et écran cuisine (KDS). · alias : KDS Baba
- **Jacob** (client) — Client restaurant — agent vocal et réservations.
- **Hashtag CBD** (client) — Client e-commerce — synchronisation Hiboutik ↔ Shopify, images produit et SEO. · alias : Hashtag
- **Multichannel** (produit) — Prospection et inbox email multicanale. · alias : outreach, Layton Multichannel
- **Layton** (produit) — Plateforme de signaux d'intention B2B. · alias : intent signals
- **Momentum** (produit) — Moteur de momentum personnel natif Omarchy : score, série, focus. · alias : score, focus
- **Momentum OS** (produit) — Version app de Momentum (React, Electron, Supabase). · alias : MomentumOS
- **Mail Hub** (produit) — Tri et alertes email multi-comptes, en lecture seule. · alias : mailhub
- **Mailspring** (produit) — Client email open source adapté à Mail Hub.
- **Mnemosyne** (produit) — Assistant d'automatisation qui observe l'écran et propose des workflows. · alias : Mnémosyne
- **Talkify** (produit) — Dictée vocale locale et privée pour Omarchy. · alias : dictée, speech-to-text
- **Ideta Cyber** (produit) — Moteur LLM hybride local/cloud pour un projet cyber. · alias : Ideta, cyber
- **Ops** (fonction) — Infrastructure, Mission Control, handbook, sites clients et studio vidéo. · alias : Mission Control, infra, vidéo
- **Restaurants** (verticale) — Verticale restauration : commandes, réservations et KDS. · alias : resto
- **Immobilier** (verticale) — Verticale immobilier : visites, rappels et gestion locative. · alias : immo
- **Médecins** (verticale) — Verticale médecins : rendez-vous, consignes et listes d'attente. · alias : médecin
- **Dentistes** (verticale) — Verticale dentistes : rendez-vous et parcours patient. · alias : dentiste
- **Coiffeurs** (verticale) — Verticale coiffeurs : réservations et blocs de temps. · alias : coiffeur
- **Notaires** (verticale) — Verticale notaires : rendez-vous et dossiers. · alias : notaire
- **SSI** (acronyme) — Parcours self-service : essai, abonnement, activation et numéro. · alias : self-service
- **KDS** (acronyme) — Kitchen Display System — écran cuisine pour les commandes. · alias : écran cuisine
- **CRM** (acronyme) — Gestion de la relation client.
- **DID** (acronyme) — Numéro de téléphone direct attribué à un agent. · alias : numéro direct
- **RLS** (acronyme) — Sécurité au niveau des lignes dans la base de données.
- **HDS** (acronyme) — Hébergement de données de santé.
- **NIS2** (acronyme) — Directive européenne de cybersécurité.
