# Journal de travail

_Simon Van de Meersche · généré le lundi 2 novembre 2026 à 08:03_

> Version partagée : les notes personnelles ne sont pas incluses.

Cette page résume le travail réalisé sur nos projets : ce qui a été livré, l'état d'avancement de chaque projet et les sujets en cours. Elle est mise à jour automatiquement à partir du code, des pull requests et des livraisons. Aucune note personnelle n'y figure. Utilise la recherche pour retrouver un sujet, un client ou un mot-clé dans tout l'historique.

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

## dimanche 1 novembre 2026

**1 PR fusionnée · 1 PR ouverte**

### Elevedia — agents vocaux

- **PR fusionnée** · SMS Factor partout — ledger provider-neutre, MO/DLR/STOP, CRM

---

## samedi 31 octobre 2026

**7 PR fusionnées · 7 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Multi-vertical voice bridge
- **PR fusionnée** · Medical voice appointments create the patient
- **PR fusionnée** · Bird adapter + signed webhook
- **PR fusionnée** · Phonic voice picker for the demo agents
- **PR fusionnée** · Route outbound SMS through Bird when SMS_PROVIDER=bird
- **PR fusionnée** · SMS Factor adapter + provider switch
- **PR fusionnée** · Redeploy API when app-sms changes

---

## vendredi 30 octobre 2026

**1 PR fusionnée · 1 PR ouverte**

### Elevedia — agents vocaux

- **PR fusionnée** · Resto demo in hub + /v1/voice/tools bridge; fix immo tools

---

## lundi 26 octobre 2026

**1 PR fusionnée · 1 PR ouverte**

### Elevedia — agents vocaux

- **PR fusionnée** · Self-serve voice agents — vérité d'activation, rollback flows, spine lifecycle, contrat d'essai

---

## vendredi 23 octobre 2026

**3 PR fusionnées · 3 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Complete births with retention policy and pre-exam instructions
- **PR fusionnée** · Formal verification: exhaustive flow explorer + call lifecycle model + agent charters
- **PR fusionnée** · Reclassify missing greeting_end as hangup-during-greeting

---

## jeudi 22 octobre 2026

**14 PR fusionnées · 7 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Acquisition provenance — lead → restaurant link, cold_email/reseau_direct
- **PR fusionnée** · Plus de fausses répétitions dans les transcriptions d'appel
- **PR fusionnée** · Le juge LLM en 2e ligne de la fiche agent
- **PR fusionnée** · Golden v1.9 — adresse à l'annonce, date de naissance, confirmation du numéro (cahier IDR)
- **PR fusionnée** · Reject truncated Belgian mobile numbers (silent SMS block)
- **PR fusionnée** · CRM directory freshness and platform detection migrations
- **PR fusionnée** · Variable {{outil}} dans l'outreach (plateforme métier détectée)
- **PR fusionnée** · Une heure tapée entre 1h00 et 1h59 un jour de changement d'heure n'est plus décalée
- **PR ouverte** · Day bounds independent of the server clock (rebase of #511)
- **PR fusionnée** · Day bounds independent of the server clock (rebase of #511)
- **PR fusionnée** · Le bandeau « retard » de l'accueil affiche ses refus en phrase lisible
- **PR fusionnée** · Thème nuit — les textes bleu marine redeviennent lisibles partout
- **PR fusionnée** · A filled honeypot must not fake a confirmation (autofill false positive)
- **PR fusionnée** · Fail2ban bans caused by missing PWA assets
- **PR fusionnée** · Honeypot returns the guard error (follow-up #688)

---

## mercredi 21 octobre 2026

**4 PR fusionnées · 5 PR ouvertes · 1 tâche**

### Elevedia — agents vocaux

- **PR fusionnée** · Client cockpit with canonical voice config (all five verticals)
- **PR fusionnée** · Install app-conductor in the dashboard Docker deps stage
- **PR fusionnée** · Dependency-aware setup checklist on all agent pages
- **Tâche** · Agent vocal : transfert d'appel, mise en mute et SMS de confirmation — Spécifications issues de la note du jour : transfert de l'agent vers le portable du restaurateur, mise en mute pour écouter la conversation, et SMS de confirmation au client.
- **PR ouverte** · Unify the client chat with the guided funnel
- **PR fusionnée** · Unify the client chat with the guided funnel

---

## mardi 20 octobre 2026

**2 PR fusionnées · 2 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Hallucinations Whisper, étapes explicites, opportunité manquante
- **PR fusionnée** · Pas de match par préfixe sur un nom à un seul mot

---

## lundi 19 octobre 2026

**8 PR fusionnées · 9 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · Plus de fausses répétitions dans les transcriptions d'appel
- **PR fusionnée** · Journal vocal — dicter une interaction sans formulaire
- **PR fusionnée** · Laisser /api/voice-log atteindre son auth token
- **PR fusionnée** · Extraction vocale sur Gemma-4 local (Anthropic HS)
- **PR fusionnée** · Schéma vocal tolérant (nulls Gemma-4) + Groq gpt-oss-120b
- **PR fusionnée** · L'annulation vocal supprime aussi l'établissement créé
- **PR fusionnée** · Normalise la raison de perte avant l'enum Postgres
- **PR fusionnée** · Résolveur vocal — pas de match sur un token générique court
- **PR fusionnée** · Groq chat opt-in + erreur LLM lisible

---

## dimanche 18 octobre 2026

**3 PR fusionnées**

### Elevedia — agents vocaux

- **PR fusionnée** · Un seul SMS par annulation de série
- **PR fusionnée** · Rappel de visite H-2 coupable par agence (cahier IDR 14-10)
- **PR fusionnée** · Book-visit enregistre la date de naissance du visiteur (cahier IDR 14-10)

---

## samedi 17 octobre 2026

**1 PR ouverte**

### Elevedia — agents vocaux

- **PR ouverte** · Portage de numéro en self-service (resto) — parcours client, file admin, relances

---

## vendredi 16 octobre 2026

**2 PR fusionnées · 3 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · Un seul SMS par annulation de série
- **PR fusionnée** · Fenêtres par prestation, RDV chaînés multi-collaborateurs, droits staff, timeline
- **PR fusionnée** · Statut de ship du patch moteur médecins (e797e9d, LIVRÉ)

---

## mercredi 14 octobre 2026

**3 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · Rappel de visite H-2 coupable par agence (cahier IDR 14-10)
- **PR ouverte** · Book-visit enregistre la date de naissance du visiteur (cahier IDR 14-10)
- **PR ouverte** · Golden v1.9 — adresse à l'annonce, date de naissance, confirmation du numéro (cahier IDR)

---

## jeudi 1 octobre 2026

**8 PR fusionnées · 8 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Dashboard P1 — tickets de table, clients, appels
- **PR fusionnée** · Réglages resto — les choix client pilotent le flow golden (v2)
- **PR fusionnée** · Liste d'attente gatée par la clé catalogue medecins.waitlist.enabled
- **PR fusionnée** · L'assistant self-serve du restaurateur — chat d'abord, garde-fous intacts
- **PR fusionnée** · Consignes pré-examen par acte (CIM² v1)
- **PR fusionnée** · Appointments.prestation_id — le RDV porte l'acte (consignes voix)
- **PR fusionnée** · Capacités bornées, prompt client, verdict du run + montage services
- **PR fusionnée** · Médecins + notaire montés (même coquille)

---

## mercredi 30 septembre 2026

**4 PR fusionnées · 5 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · Registry(diagrammes): specs flux-appel (gabarit schémas tldraw)
- **PR fusionnée** · SSI-4 — onboarding immo : étape formule + reprise au bon endroit
- **PR fusionnée** · KDS Baba P1 : n° de table figé + passe bar « Plat prêt » + alertes par poste
- **PR fusionnée** · Dashboards clients depuis demo.elevedia.be sans accès admin
- **PR fusionnée** · Resto births get their public booking_slug

---

## mardi 29 septembre 2026

**10 PR fusionnées · 10 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Clonage de voix + cartes voix sur la page agent (alignement phase A)
- **PR fusionnée** · Page agent alignée sur les 4 autres verticales (phase B)
- **PR fusionnée** · Dashboard: marquer les tours agent non prononcés (transcription)
- **PR fusionnée** · Passer full_name au createUser — la naissance médecins mourait à l'étape 1
- **PR fusionnée** · Parité — colonne notifications, schéma Drizzle, garde naissance (phase C)
- **PR fusionnée** · SSI-1 (v1) — essai sans carte : cap des appels test + un essai par téléphone
- **PR fusionnée** · Ops(birth): banc de naissance médecins versionné (smoke dev)
- **PR fusionnée** · SSI-2 — checkout abonnement immo → activation automatique
- **PR fusionnée** · La recette bloquante ne se mettait plus en file depuis le 26-09
- **PR fusionnée** · SSI-3 (immo) — une seule source de prix + portail self-service

---

## lundi 28 septembre 2026

**2 PR fusionnées · 2 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Clonage de voix client via Gradium (4 dashboards)
- **PR fusionnée** · SSI-0 (D2) — le DID se claim à l'activation, plus à la naissance

---

## dimanche 27 septembre 2026

**1 PR fusionnée · 1 PR ouverte**

### Elevedia — agents vocaux

- **PR fusionnée** · Duplex_resume + registre de comportement — les naissances héritent de tous les fixes

---

## samedi 26 septembre 2026

**4 PR fusionnées · 6 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Quota atteint = surconsommation comptée, jamais de pause
- **PR fusionnée** · La migration quota-overage cible consume_minutes (pas consume_new_call_minutes)
- **PR fusionnée** · Quota atteint = surconsommation comptée, jamais de pause
- **PR ouverte** · Une relance sur 5xx/timeout — la confirmation ne part plus en fumée
- **PR ouverte** · Le juge LLM en 2e ligne de la fiche agent
- **PR fusionnée** · Parité de la page /agent avec le client resto

---

## vendredi 25 septembre 2026

**6 PR fusionnées · 6 PR ouvertes**

### Elevedia — agents vocaux

- **PR fusionnée** · Résa invité sans compte sur le site public
- **PR fusionnée** · Parité admin Imovia ↔ Elevedia : agences, analytics, rapports, usage
- **PR fusionnée** · Admin Imovia : page Agents vocaux (liste + fiche agent canonique)
- **PR fusionnée** · Admin Imovia — vérif agents : bug sync numéros, numéro assignable, horaires d'ouverture
- **PR fusionnée** · Admin Imovia — garde-fou numéros : le pool ne peut plus voler un numéro d'une autre verticale
- **PR fusionnée** · HOTFIX — garde-fou pool : basé sur le trunk LiveKit, pas la connexion Telnyx

---

## jeudi 24 septembre 2026

**2 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · Variable {{outil}} dans l'outreach (plateforme métier détectée)
- **PR ouverte** · Crm_directory_plateformes — plateformes métier des fiches (détection, annuaires, file)

---

## mercredi 23 septembre 2026

**13 PR fusionnées · 14 PR ouvertes**

### Elevedia — agents vocaux

- **PR ouverte** · Security(db): lock down users, definer functions, RLS (migrations NOT applied)
- **PR fusionnée** · Security: lock admin server actions + app_metadata role checks
- **PR fusionnée** · Security: backend fixes (Mollie, SMS pumping, SSRF, IDOR, fail-closed crons)
- **PR fusionnée** · Security(crm): app_metadata roles + ownership checks
- **PR fusionnée** · Security: OAuth callbacks, immo roles, fail-closed crons, tenant filters
- **PR fusionnée** · Public booking limits, customer no-overwrite, server-proven onboarding phone
- **PR fusionnée** · Dashboard: touch-first pass (tablette, doigts, mots simples)
- **PR fusionnée** · Nouveaux agents nés avec la voix Cartesia Inès
- **PR fusionnée** · Cap anonymous order creation (anti SMS/email/kitchen abuse)
- **PR fusionnée** · Sec: CRM gcal OAuth state signing, .env ignore, sharp 0.35.4
- **PR fusionnée** · Close birth parity gaps (immo admin wizard, notaire golden, fr+nl, demos)
- **PR fusionnée** · Sec: invisible anti-bot guard on public forms + medecins signup limits
- **PR fusionnée** · Cartesia credit tracking + premium-voice fallback alert

### Multichannel — outreach

- **PR fusionnée** · Never ingest our own mail as a prospect reply

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
