# Journal de travail

_Simon Van de Meersche · généré le jeudi 22 octobre 2026 à 11:13_

> Version partagée : les notes personnelles ne sont pas incluses.

## mercredi 21 octobre 2026

**4 PR fusionnées, 5 PR ouvertes, 6 commits et 1 tâche sur 3 projets.**

### Elevedia — agents vocaux

- **PR fusionnée** · [feat(conductor): client cockpit with canonical voice config (all five verticals)](https://github.com/Tegath/elevedia/pull/679) · `Tegath/elevedia`
- **PR fusionnée** · [fix(immo): install app-conductor in the dashboard Docker deps stage](https://github.com/Tegath/elevedia/pull/680) · `Tegath/elevedia`
- **PR fusionnée** · [feat(activation): dependency-aware setup checklist on all agent pages](https://github.com/Tegath/elevedia/pull/681) · `Tegath/elevedia`
- **Tâche** · Agent vocal : transfert d'appel, mise en mute et SMS de confirmation — Spécifications issues de la note du jour : transfert de l'agent vers le portable du restaurateur, mise en mute pour écouter la conversation, et SMS de confirmation au client.
- **4 commits** · `Tegath/elevedia`
  - [feat(conductor): client cockpit with canonical voice config (all five verticals) (#679)](https://github.com/Tegath/elevedia/commit/1f3d5c30434299ad22c07cb94efed080aa9628ef) · `1f3d5c3`
  - [fix(immo): install app-conductor in the dashboard Docker deps stage (#680)](https://github.com/Tegath/elevedia/commit/90f17b5fb8b0083017f5c0836d8aa76edc5fe7e2) · `90f17b5`
  - [feat(activation): dependency-aware setup checklist on all agent pages (#681)](https://github.com/Tegath/elevedia/commit/993c57429ffc47dda62a3f41d6913166122e4783) · `993c574`
  - [feat(conductor): unify the client chat with the guided funnel (#683)](https://github.com/Tegath/elevedia/commit/e6690a4ae30175a1eaf32ff8ccc75913698fd734) · `e6690a4`
- **PR ouverte** · [feat(conductor): unify the client chat with the guided funnel](https://github.com/Tegath/elevedia/pull/682) · `Tegath/elevedia`
- **PR fusionnée** · [feat(conductor): unify the client chat with the guided funnel](https://github.com/Tegath/elevedia/pull/683) · `Tegath/elevedia`

### Momentum

- **1 commit** · `momentum`
  - Tâches : sidebar zones/projets façon Things 3 · `5e1eeaf`

### Hashtag CBD

- **1 commit** · `Tegath/hashtag-sync`
  - [feat(seo): OpenCode Go backend with round-robin key pool](https://github.com/Tegath/hashtag-sync/commit/968aa550184be713cd290358685b4fb59bd1f15c) · `968aa55`

---

## mardi 20 octobre 2026

**2 PR fusionnées, 2 PR ouvertes et 10 commits sur 4 projets.**

### Elevedia — agents vocaux

- **1 commit** · `Tegath/elevedia-web`
  - [chore(directory): scheduled sync (client edits)](https://github.com/Tegath/elevedia-web/commit/df4a8ab968ed9d7c418a862ac98e9086b04657a2) · `df4a8ab`
- **2 commits** · `Tegath/elevedia`
  - [fix(crm): filtre hallucinations Whisper, etapes explicites et opportunite manquante](https://github.com/Tegath/elevedia/commit/da1e614f20e0a703eb41aec12980592cac3c4090) · `da1e614`
  - [fix(crm): pas de match par prefixe sur un nom a un seul mot](https://github.com/Tegath/elevedia/commit/0dcccb63dbeee53e64f8bc5a72d7400b381a291f) · `0dcccb6`
- **PR fusionnée** · [fix(crm): hallucinations Whisper, étapes explicites, opportunité manquante](https://github.com/Tegath/elevedia/pull/677) · `Tegath/elevedia`
- **PR fusionnée** · [fix(crm): pas de match par préfixe sur un nom à un seul mot](https://github.com/Tegath/elevedia/pull/678) · `Tegath/elevedia`

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

**8 PR fusionnées, 9 PR ouvertes et 21 commits sur 4 projets.**

### Elevedia — agents vocaux

- **PR ouverte** · [fix(dashboards): plus de fausses répétitions dans les transcriptions d'appel](https://github.com/Tegath/elevedia/pull/668) · `Tegath/elevedia`
- **PR fusionnée** · [feat(crm): journal vocal — dicter une interaction sans formulaire](https://github.com/Tegath/elevedia/pull/669) · `Tegath/elevedia`
- **PR fusionnée** · [fix(crm): laisser /api/voice-log atteindre son auth token](https://github.com/Tegath/elevedia/pull/670) · `Tegath/elevedia`
- **PR fusionnée** · [feat(crm): extraction vocale sur Gemma-4 local (Anthropic HS)](https://github.com/Tegath/elevedia/pull/671) · `Tegath/elevedia`
- **PR fusionnée** · [fix(crm): schéma vocal tolérant (nulls Gemma-4) + Groq gpt-oss-120b](https://github.com/Tegath/elevedia/pull/672) · `Tegath/elevedia`
- **PR fusionnée** · [fix(crm): l'annulation vocal supprime aussi l'établissement créé](https://github.com/Tegath/elevedia/pull/673) · `Tegath/elevedia`
- **PR fusionnée** · [fix(crm): normalise la raison de perte avant l'enum Postgres](https://github.com/Tegath/elevedia/pull/674) · `Tegath/elevedia`
- **PR fusionnée** · [fix(crm): résolveur vocal — pas de match sur un token générique court](https://github.com/Tegath/elevedia/pull/675) · `Tegath/elevedia`
- **16 commits** · `Tegath/elevedia`
  - [fix(services-dashboard): customer search refetched on picker open + email matching](https://github.com/Tegath/elevedia/commit/6e3b17509915859b5475d2f2cc79dcaf679a1362) · `6e3b175`
  - [feat(resto): per-client same-day booking delay](https://github.com/Tegath/elevedia/commit/77b45ca1932637ecf95dc21b9a69a26ad9c43327) · `77b45ca`
  - [feat(resto): transfer hours — per-client window in the dashboard](https://github.com/Tegath/elevedia/commit/940d2f9a47bfea8198db570acf1e5b9937d67af1) · `940d2f9`
  - [feat(crm): journal vocal — dicter une interaction et l'écrire immédiatement](https://github.com/Tegath/elevedia/commit/189a0da72db60d2eecc5c64d263f7be87f6b5f63) · `189a0da`
  - [fix(crm): /api/voice-log doit accepter le Bearer token sans session](https://github.com/Tegath/elevedia/commit/d845cfcf2d9a3c22c112f7fd0948ecb6e4b62b5b) · `d845cfc`
  - [feat(crm): extraction vocale sur Gemma-4 local, Groq en secours, Anthropic en dernier](https://github.com/Tegath/elevedia/commit/cca0dd725cbb0f6e114aeb2fe6953eaee0d9586c) · `cca0dd7`
  - [fix(crm): accepte les nulls de Gemma-4, Groq gpt-oss-120b par defaut](https://github.com/Tegath/elevedia/commit/7f9a99a5b1fae206ccc9907d176e9198e9460b8a) · `7f9a99a`
  - [fix(crm): l'annulation supprime aussi l'etablissement cree par la dictee](https://github.com/Tegath/elevedia/commit/c3aa2ab8965b5a42525d41bb361659f95d68f16e) · `c3aa2ab`
  - [fix(crm): normalise raison_perte avant l'enum Postgres](https://github.com/Tegath/elevedia/commit/60dbed9cef275ee01d129e37cbbbf69248d66ad3) · `60dbed9`
  - [fix(crm): le resolveur ne matche plus un token generique court](https://github.com/Tegath/elevedia/commit/595eb898a4165e79f5524b4e33b11f7c5532c7a7) · `595eb89`
  - [fix(crm): Groq chat en opt-in et erreur LLM lisible](https://github.com/Tegath/elevedia/commit/a3a7caa78b20f37e8919d55584005ca8dd2274aa) · `a3a7caa`
  - [feat(settings): transfer hours on services, notaire and immo dashboards](https://github.com/Tegath/elevedia/commit/71028caae267c0df2d50d9ddaca82f0b94ed56bc) · `71028ca`
  - [feat(settings): same-day booking delay on non-resto verticals](https://github.com/Tegath/elevedia/commit/53e37fecf02d93ba762adb9d817e1359b54a51b2) · `53e37fe`
  - [chore(voice-config): sync conductor doctrine — booking_notice cap](https://github.com/Tegath/elevedia/commit/942c6b500ebfce738cd4fbd8d44aebd38cbd5cc1) · `942c6b5`
  - [ci(deploy): immo-dashboard redeploys on app-settings changes](https://github.com/Tegath/elevedia/commit/ce01300dddcc79ea9391efa4b4e22c5475e77a5b) · `ce01300`
  - [fix(immo): copy app-settings package.json in the Docker deps stage](https://github.com/Tegath/elevedia/commit/4d481e0d9b1d5282e28384c57a70e32a075a3cfc) · `4d481e0`
- **PR fusionnée** · [fix(crm): Groq chat opt-in + erreur LLM lisible](https://github.com/Tegath/elevedia/pull/676) · `Tegath/elevedia`

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

**3 PR fusionnées et 32 commits sur 2 projets.**

### Elevedia — agents vocaux

- **PR fusionnée** · [fix(services-dashboard): un seul SMS par annulation de série](https://github.com/Tegath/elevedia/pull/664) · `Tegath/elevedia`
- **PR fusionnée** · [feat(immo): rappel de visite H-2 coupable par agence (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/661) · `Tegath/elevedia`
- **PR fusionnée** · [feat(immo): book-visit enregistre la date de naissance du visiteur (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/662) · `Tegath/elevedia`
- **28 commits** · `Tegath/elevedia`
  - [fix(realtime): port refresh-board channel prefix to the 3 other dashboards](https://github.com/Tegath/elevedia/commit/c97577fc4e0002dd679e057cff336ee1a0de7a32) · `c97577f`
  - [chore(medecins-landing): expose typecheck (tsc --noEmit) pour le gate CI](https://github.com/Tegath/elevedia/commit/9f7c094799be0f21556ab0486e90dfa6fe95ab5e) · `9f7c094`
  - [fix(voice-config): le skip du golden flow est typé et visible au go-live](https://github.com/Tegath/elevedia/commit/2772766889af0fccf1b90339fe10f0b7c51bb1ac) · `2772766`
  - [fix(onboarding): les échecs de numéro ne sont plus silencieux](https://github.com/Tegath/elevedia/commit/7bff94c97997e6f694eedd43a86b412d6f2e5664) · `7bff94c`
  - [docs: audit complet du code (7 causes racines, 15 P0) — 2026-10-18](https://github.com/Tegath/elevedia/commit/408f0f934ab0deaa528c30b11b57a4444fa22827) · `408f0f9`
  - [ci(deploy): câbler les suites web, réparer les filtres, échouer fort sur les skips](https://github.com/Tegath/elevedia/commit/1baf8956232a92605dc1bc33f2a52d0d8f8a38f3) · `1baf895`
  - [test(dashboard): suites mortes relancées, assertions alignées](https://github.com/Tegath/elevedia/commit/0facf425fb087d6df9747876581f0106887cd8ec) · `0facf42`
  - [ci(bpmn): déployer tout fichier changé dans le push, pas seulement HEAD~1](https://github.com/Tegath/elevedia/commit/fff9d8dbaabfa29df62b0e49a14ed9977bc5be5e) · `fff9d8d`
  - [test(dashboard): 4 suites chargeables hors Next (mock server-only + service)](https://github.com/Tegath/elevedia/commit/55256ae6615334c83b41ccfc9fe055fa61f64551) · `55256ae`
  - [ci(deploy): ratchets statiques au gate + flock 1020 s + checker de filtres](https://github.com/Tegath/elevedia/commit/419b8c8c483a679e6b890157e66bb48f0807e3c0) · `419b8c8`
  - [feat(app-sms): cliquet anti-SMS ad-hoc hors du paquet partagé](https://github.com/Tegath/elevedia/commit/b571e87742e0026af7f771476748b3bb8cb36044) · `b571e87`
  - [feat(rls): user_clinic_ids/user_agency_ids/user_business_ids + cliquet des policies](https://github.com/Tegath/elevedia/commit/aeb7531ac1ee0de1f4ed7553b8543c1beef1cde5) · `aeb7531`
  - [fix(dashboard): une écriture à 0 ligne n'est plus un succès (assertWrite)](https://github.com/Tegath/elevedia/commit/d3ec7fac128d1a03feacc4cf224dc2ef2f6699da) · `d3ec7fa`
  - [ci(rollback): workflow de restauration par sha (remplace le ssh+retag manuel)](https://github.com/Tegath/elevedia/commit/0d935e74d34206e3a9a9ba5b7fd92e3d4ca90a0a) · `0d935e7`
  - [fix(medecins): l'accueil passe par saveGreetingCore (fin de la copie locale)](https://github.com/Tegath/elevedia/commit/08e17d8dfb53c1e8b24a2809459b5816ae8e0961) · `08e17d8`
  - [fix(vite): typecheck des 4 sites passable (vite/client + erreurs sales-pwa)](https://github.com/Tegath/elevedia/commit/d59247d9d861297037cd20c90939810572986c38) · `d59247d`
  - [ci(deploy): sonde de contenu — l'image servie doit être celle du sha du run](https://github.com/Tegath/elevedia/commit/fa66d33272f469d5f81e58959cfc3e5d13581931) · `fa66d33`
  - [ci(rollback): résoudre les sha courts contre les tags de l'hôte](https://github.com/Tegath/elevedia/commit/dac7508b9787d869ee4b8d376d19d62ab531c9d2) · `dac7508`
  - [docs(db-immo,db-services): bannière orphelin — aucune app ne les importe](https://github.com/Tegath/elevedia/commit/3742a98d6a8d54c5797178afebe92d05384c56d6) · `3742a98`
  - [ci(deploy): corrige /docker/immo → /docker/imovia dans la sonde](https://github.com/Tegath/elevedia/commit/1bc1552e2c90da93f557e266934e72a9fdbbabbc) · `1bc1552`
  - [feat(rls): rebranchement des policies sur user_*_ids() — appliqué et vérifié en prod](https://github.com/Tegath/elevedia/commit/14521fe588c10d263af756cc2ddd7d56aa589cc1) · `14521fe`
  - [test(services): garde le happy path du tunnel public (1 résa = 1 insert + 1 SMS)](https://github.com/Tegath/elevedia/commit/5aaffb73269b4aed3aa4913f49200793c66bd144) · `5aaffb7`
  - [fix(services-booking): waitlist durcie (honeypot, tél, 423/429) — parité médecins](https://github.com/Tegath/elevedia/commit/fb99817a8b3dadc5ab63846f36da8fb0648a71f8) · `fb99817`
  - [fix(notaire): recherche clients accents/téléphone + 23505 fiche existante (parité services)](https://github.com/Tegath/elevedia/commit/bc99e9d551fc9b0c333f68126dad1c167b8dc651) · `bc99e9d`
  - [fix(notaire): SMS — un seul récap par série annulée + garde activation (parité services)](https://github.com/Tegath/elevedia/commit/f40f7fff738369eaf3432b305d0cc49d2415008a) · `f40f7ff`
  - [feat(immo-dashboard): per-agency switch for the H-2 visit reminder (#661)](https://github.com/Tegath/elevedia/commit/147623486ca3d6a17df79e1b8d264c320f5a3e4f) · `1476234`
  - [feat(immo): book-visit stores visitor_dob (ISO) with pre-migration fallback (#662)](https://github.com/Tegath/elevedia/commit/b25a7482b2ce8e946346d704a52a2375a79aa1ae) · `b25a748`
  - [feat(observability): backchannel marker shows question/gap context + legend entries (placement audit phase 1)](https://github.com/Tegath/elevedia/commit/1b3876b4ad3401b416d0fea9a407d2b6a07a79a5) · `1b3876b`

### Momentum

- **4 commits** · `momentum`
  - Ambiances sonores : la musique du focus, tes fichiers en boucle · `47f238d`
  - Réglages : choisir son ambiance dans le tableau de bord · `1cf048f`
  - HUD : la pastille ne s'anime que si elle est visible et qu'un focus tourne · `0ee810e`
  - HUD : la pastille ne redessine plus en boucle au repos · `390a101`

---

## samedi 17 octobre 2026

**1 PR ouverte et 11 commits sur 3 projets.**

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

### Elevedia — agents vocaux

- **PR ouverte** · [Portage de numéro en self-service (resto) — parcours client, file admin, relances](https://github.com/Tegath/elevedia/pull/667) · `Tegath/elevedia`

---

## vendredi 16 octobre 2026

**2 PR fusionnées, 3 PR ouvertes et 11 commits sur 2 projets.**

### Elevedia — agents vocaux

- **PR ouverte** · [fix(services-dashboard): un seul SMS par annulation de série](https://github.com/Tegath/elevedia/pull/664) · `Tegath/elevedia`
- **6 commits** · `Tegath/elevedia`
  - [feat(medecins): inbox — statuts réversibles (Traité ↔ À traiter) + « Voir l'appel » sur les rappels](https://github.com/Tegath/elevedia/commit/b73cf7580c2c7fcf56b1e3fd723c1c65362237d0) · `b73cf75`
  - [fix(immo-dashboard): voice-context retourne tout le catalogue actif (30 lignes arbitraires -> 100 + tri stable)](https://github.com/Tegath/elevedia/commit/4cbbfa04f268d31680ef459e347b90521521dc2b) · `4cbbfa0`
  - [fix(services-dashboard): one SMS per cancelled series, not one per occurrence](https://github.com/Tegath/elevedia/commit/f4e83c0a3ac6b2e3fc156b02f69787a3a35f60f7) · `f4e83c0`
  - [feat(medecins): fenêtres par prestation, RDV chaînés multi-collaborateurs, droits staff, timeline (#665)](https://github.com/Tegath/elevedia/commit/5e4f548f59f9981b5e9d3855b9fb751d92aed3f9) · `5e4f548`
  - [docs: spec self-service number porting (all verticals)](https://github.com/Tegath/elevedia/commit/3dc265dbaf3a68933bcff804daac452db55a8504) · `3dc265d`
  - [docs(voice): médcins chaînés + fenêtres — statut SHIPPÉ (release e797e9d, gate VERT, flotte VIVANT) (#666)](https://github.com/Tegath/elevedia/commit/6f7e4aef9fe41a7d3734987642e61c29247813ab) · `6f7e4ae`
- **PR fusionnée** · [feat(medecins): fenêtres par prestation, RDV chaînés multi-collaborateurs, droits staff, timeline](https://github.com/Tegath/elevedia/pull/665) · `Tegath/elevedia`
- **PR fusionnée** · [docs(voice): statut de ship du patch moteur médecins (e797e9d, LIVRÉ)](https://github.com/Tegath/elevedia/pull/666) · `Tegath/elevedia`

### Momentum

- **5 commits** · `momentum`
  - Momentum : moteur de momentum natif Omarchy · `261c294`
  - v0.2 : tableau de bord complet, habitudes, OKR, revues, XP et quêtes · `73db7f5`
  - Sons arcade et animations de palier (v0.3) · `8ff8f4b`
  - Fx : les sons d'interface ne dépendent plus des animations · `2419bda`
  - v0.4 : sous-tâches validables, HUD de focus, anneau animé dans la barre · `bf09123`

---

## jeudi 15 octobre 2026

**2 commits.**

### Elevedia — agents vocaux

- **2 commits** · `Tegath/elevedia`
  - [feat(medecins): brief Lecomte 15-10 — voir l'appel, ajouter un patient, heure libre](https://github.com/Tegath/elevedia/commit/f307ab96c618b24f17f4b836af9eac192245248f) · `f307ab9`
  - [fix(medecins): le détail d'appel redevient joignable + doublon fiche créée](https://github.com/Tegath/elevedia/commit/91b5ad32ef28eb478870162651ad36c917fe7dcd) · `91b5ad3`

---

## mercredi 14 octobre 2026

**3 PR ouvertes et 5 commits.**

### Elevedia — agents vocaux

- **5 commits** · `Tegath/elevedia`
  - [fix(services-dashboard): la recherche retrouve les fiches clients](https://github.com/Tegath/elevedia/commit/3919e9370e331081629fa0d397230b5c6afd294f) · `3919e93`
  - [fix(services-dashboard): une fiche client saisie manuellement reste enregistrée](https://github.com/Tegath/elevedia/commit/c2601848338a334b7b2a1b50eb4f5cfaa84a10ab) · `c260184`
  - [fix(medecins): inbox rows wrap on mobile instead of overlapping](https://github.com/Tegath/elevedia/commit/6abf6eecc96d45b930e7689122af283f5ac16bbb) · `6abf6ee`
  - [fix(medecins): bookable slots step by the appointment duration, not a fixed 15-min grid](https://github.com/Tegath/elevedia/commit/5379a128907421ceb0e6808e3cd8018e3eac147e) · `5379a12`
  - [feat(medecins): vue agenda « Par praticien » — une colonne par médecin](https://github.com/Tegath/elevedia/commit/3dc0ccff3ed5b33ff124406ab0ae2627bcdf09ba) · `3dc0ccf`
- **PR ouverte** · [feat(immo): rappel de visite H-2 coupable par agence (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/661) · `Tegath/elevedia`
- **PR ouverte** · [feat(immo): book-visit enregistre la date de naissance du visiteur (cahier IDR 14-10)](https://github.com/Tegath/elevedia/pull/662) · `Tegath/elevedia`
- **PR ouverte** · [feat(flow-immo): golden v1.9 — adresse à l'annonce, date de naissance, confirmation du numéro (cahier IDR)](https://github.com/Tegath/elevedia/pull/663) · `Tegath/elevedia`

---

## mardi 13 octobre 2026

**14 commits.**

### Elevedia — agents vocaux

- **4 commits** · `Tegath/elevedia-web`
  - [feat(fiche): avis first-party prets - carte 'Avis verifies' + AggregateRating des 5 avis (jamais les avis Google) ; sync expose firstPartyReviews](https://github.com/Tegath/elevedia-web/commit/c73dd84456684b22280aff63bf317a3769e21b8f) · `c73dd84`
  - [seo(maillage): lot 2 - 8 liens contextuels poses (pipeline GSC ; claude OAuth expire -> vet fallback gpt-6-luna ; fix journal apply.py)](https://github.com/Tegath/elevedia-web/commit/57b82dc189a2b215b068d3923d05ba1490a3aa46) · `57b82dc`
  - [fix(fiche): durcir le JSON-LD (escape </script> dans les 3 gabarits tenant), ratingValue en Number, etoiles et date robustes (avis first-party)](https://github.com/Tegath/elevedia-web/commit/5148d264ea9ee2377c37675ca46d07eed55a8358) · `5148d26`
  - [seo(maillage): retirer 2 liens du lot 2 apres revue adverse (ancre negative / accueil humain vs automatique) - 6 liens solides restent](https://github.com/Tegath/elevedia-web/commit/1c7a7a5e9eceff5483f32ca9d78a2239f8aa2886) · `1c7a7a5`
- **10 commits** · `Tegath/elevedia`
  - [feat(vitrines): footer badge opt-in - la fiche hub du client remplace le hub vertical quand le client a dit oui (liste vide = zero changement visible)](https://github.com/Tegath/elevedia/commit/a8d3f58109543e32ed85c1a4d0c70edb9dd2c9da) · `a8d3f58`
  - [feat(medecins): carte admin « Fonctionnalités » — retranscription d'appels activable par cabinet](https://github.com/Tegath/elevedia/commit/8a9ecbda2242bb32508aab1d9f886b08dfb0f3f7) · `8a9ecbd`
  - [fix(medecins): actions admin — rôle lu dans public.users, plus d'app_metadata](https://github.com/Tegath/elevedia/commit/f9ebebacf2a5f4f1cbd3633bae16ffab492d9f1a) · `f9ebeba`
  - [feat(notaire-dashboard): visit days survive reopening — infer the recurring pattern from saved slots](https://github.com/Tegath/elevedia/commit/c09166597ef2c0f827191c12969dfaa995ed7fcd) · `c091665`
  - [feat(services): endpoint MCP read-only (fiches + disponibilites live) pour le rail agentique - 3 outils, JSON-RPC 2.0, zero ecriture](https://github.com/Tegath/elevedia/commit/ab0153e83bcc7b7a18db74048e00753c636f79d5) · `ab0153e`
  - [feat(medecins): journal de conformite (CSV) - trace par appel + preuve mention IA, scope cabinet, caps ; retention constatee 30/90j](https://github.com/Tegath/elevedia/commit/27cb48262c7ed76317feaadc48cdaaa6efb54091) · `27cb482`
  - [fix(medecins): compliance - 500 generiques (pas de fuite PostgREST), tri secondaire id, note retention precise](https://github.com/Tegath/elevedia/commit/c9b9b269d8063406729e023b0238b5aeecabba2b) · `c9b9b26`
  - [fix(services): mcp - middleware public (api/mcp exclu du login), CORS Mcp-Protocol-Version, filtre commente](https://github.com/Tegath/elevedia/commit/ca486c7cd742c2a71116fa9035ffbed3874cd630) · `ca486c7`
  - [fix(medecins): le détail d'appel client n'affiche plus le lecteur audio](https://github.com/Tegath/elevedia/commit/c59f6b65881e5ac3980f5495d08bc14ffe181128) · `c59f6b6`
  - [feat(medecins): onglet Appels — compte rendu détaillé du moteur + motif dans l'historique](https://github.com/Tegath/elevedia/commit/fc80203a8e19fe5c990b9a1387baeabef5e59337) · `fc80203`

---

## lundi 12 octobre 2026

**3 commits.**

### Elevedia — agents vocaux

- **2 commits** · `Tegath/elevedia`
  - [feat(settings): transfer hours — shared editor + doctors agent wiring](https://github.com/Tegath/elevedia/commit/7f972ef7ae72298ba0819c9a1166ed458e12cfc0) · `7f972ef`
  - [feat(medecins): cancellation reason menu + SMS with reason and booking link](https://github.com/Tegath/elevedia/commit/b11d9fb838a13eaf60fab20f7a96c03dacbeff19) · `b11d9fb`
- **1 commit** · `Tegath/elevedia-web`
  - [chore(directory): scheduled sync (client edits)](https://github.com/Tegath/elevedia-web/commit/7666a21dce16bc38dfa3fdd9f5cb6b81e9108e27) · `7666a21`

---

## dimanche 11 octobre 2026

**1 commit.**

### Momentum OS

- **1 commit** · `Tegath/momentumos`
  - [feat(areas-drive): bouton Copier — le document devient UNE tâche, sans IA](https://github.com/Tegath/momentumos/commit/fb4e714db75e0c2b652c7a33cf3175772431abb7) · `fb4e714`

---

## samedi 10 octobre 2026

**18 commits sur 2 projets.**

### Momentum OS

- **9 commits** · `Tegath/momentumos`
  - [feat(areas): dossiers Drive liés aux areas — navigation, import en tâches, nouveau doc](https://github.com/Tegath/momentumos/commit/9ceafe535b6679ae00fbeef2eafe93ee9034f9b5) · `9ceafe5`
  - [fix(import): message explicite quand le crédit Anthropic Console est épuisé](https://github.com/Tegath/momentumos/commit/00a47aebd6d89fd5245990036bc7c8826632c534) · `00a47ae`
  - [feat(areas): Drive via OAuth Google par utilisateur (les clés SA sont interdites par l'org)](https://github.com/Tegath/momentumos/commit/d7d0e631e5f2cea0073575d94330d2db64ba799e) · `d7d0e63`
  - [fix(areas-drive): fallback sur la connexion Google du propriétaire du workspace](https://github.com/Tegath/momentumos/commit/8286e041b51b18a4244509587b262cd07b5a37da) · `8286e04`
  - [fix(areas): le header ne se ratatine plus — wrap des contrôles au lieu du chevauchement](https://github.com/Tegath/momentumos/commit/fa202d21362d7e6bd6aee6823b6d460300d075b5) · `fa202d2`
  - [feat(areas): la barre Drive suit aussi la sélection d'un projet (via son area)](https://github.com/Tegath/momentumos/commit/e864688634485b0cce1b6e12b1be43e88a634cd5) · `e864688`
  - [fix(areas): la page ne passe plus sous la barre sticky des indicateurs](https://github.com/Tegath/momentumos/commit/c234283c203f30983628231d39af84b0e01bf62b) · `c234283`
  - [feat(areas-drive): navigateur de dossiers + tâche depuis un dossier (sans IA)](https://github.com/Tegath/momentumos/commit/c95717bc9641b7801002134c6701a39d53fd988d) · `c95717b`
  - [feat(areas-drive): Parcourir démarre dans le Drive partagé de l'équipe](https://github.com/Tegath/momentumos/commit/16306d5544e9ece1cb610692c074142dfd584d89) · `16306d5`

### Elevedia — agents vocaux

- **1 commit** · `Tegath/elevedia`
  - [fix(birth): immo — le socle est appliqué à la naissance (ligne core semée le 27-09 : la porte refusait TOUTE naissance immo — clés duplex_resume/turn_gap_listen)](https://github.com/Tegath/elevedia/commit/eae52e893964e85496062d0c49a0eea0c6b2b0fd) · `eae52e8`
- **8 commits** · `Tegath/elevedia-web`
  - [feat(seo): page sous-métier ORL + vague NL (6 pages, hreflang fr↔nl)](https://github.com/Tegath/elevedia-web/commit/86d6bea25771c154cc913ae1d99995228b2b079d) · `86d6bea`
  - [docs(hub): notes NL (CLAUDE.md) + URLs NL dans llms.txt](https://github.com/Tegath/elevedia-web/commit/467fea12ce34b049000a9ff72a4e69008a310ddd) · `467fea1`
  - [docs(seo-maillage): cron GSC hebdo installé (GO 2026-10-10) + accès sc-domain débloqué](https://github.com/Tegath/elevedia-web/commit/a23ec867e33fced898e6cbee6f6c3aff8f94a629) · `a23ec86`
  - [feat(seo): première fournée sous-métiers — coiffeur, dentaire, brasserie (FR + paires NL)](https://github.com/Tegath/elevedia-web/commit/82f630c09dfc1c4627827b75c8ed9c29f5723506) · `82f630c`
  - [feat(seo): vague 2 — 6 métiers × 2 langues (kiné, vétérinaire, institut, garage, friterie, pizzeria)](https://github.com/Tegath/elevedia-web/commit/215603a0b48fbd504136a29b8c4c069792612250) · `215603a`
  - [feat(moat): radar GEO (52 prompts, 3 moteurs, baseline prête) + IndexNow (clé publique + script npm)](https://github.com/Tegath/elevedia-web/commit/24a476949c7d1c52b1ab5bd0303b9da1d9bcfb4b) · `24a4769`
  - [feat(geo-radar): moteurs go-* (opencode-go: gpt/claude/grok/deepseek) + cron hebdo installé + garde anti-contamination](https://github.com/Tegath/elevedia-web/commit/d5ae1ea1a562e95573aaa71a1592999b4e5de9f3) · `d5ae1ea`
  - [feat(geo-radar): run parallèle --workers (4x) + cron --workers 4](https://github.com/Tegath/elevedia-web/commit/503390f1aa23c23415fbd85a97b91d84c7a356e3) · `503390f`

---

## vendredi 9 octobre 2026

**7 commits.**

### Elevedia — agents vocaux

- **1 commit** · `Tegath/elevedia-web`
  - [chore(directory): scheduled sync (client edits)](https://github.com/Tegath/elevedia-web/commit/49d47d5e7980edd713570d69215a570c9dba2b5e) · `49d47d5`
- **6 commits** · `Tegath/elevedia`
  - [feat(resto): A rappeler queue for missed transfers in notifications](https://github.com/Tegath/elevedia/commit/585c5e1c9457be10f2204c6616c490e147b631ac) · `585c5e1`
  - [feat(dashboard): widget de réservation embarquable (/embed + embed.js)](https://github.com/Tegath/elevedia/commit/18039b006242fca6332194fe81893ff4f4d2e04e) · `18039b0`
  - [fix(dashboard): embed — l'iframe rétrécit aussi (hauteur mesurée sur le body)](https://github.com/Tegath/elevedia/commit/0b9062bcb790ff450e06c179fd480429a6e3a27b) · `0b9062b`
  - [feat(dashboard): guide d'installation pour clients non-tech (onglet Réservation en ligne)](https://github.com/Tegath/elevedia/commit/fa441b5b451b1710ef0c98a6efd44aba587374f8) · `fa441b5`
  - [feat(services-dashboard): libellés courts des prestations (nom parlé par l'agent) + doc ops](https://github.com/Tegath/elevedia/commit/4d1fdc6bfc9f5898447d9d078b95b144ae9cedf0) · `4d1fdc6`
  - [feat(db-medecins): version clinic_flows + clinic_flow_templates DDL (prod-only tables, audit 26-09)](https://github.com/Tegath/elevedia/commit/4b91eb57599b4bb88c5e9edb8004ea2b02deeddd) · `4b91eb5`

---

## jeudi 8 octobre 2026

**19 commits sur 3 projets.**

### Elevedia — agents vocaux

- **1 commit** · `Tegath/elevedia-web`
  - [chore(directory): scheduled sync (client edits)](https://github.com/Tegath/elevedia-web/commit/84dffcd2354a53a4639b9a14d11996535d4ce617) · `84dffcd`
- **12 commits** · `Tegath/elevedia`
  - [feat(calls): recherche full-text des transcripts — tsvector + RPC search_calls + route admin](https://github.com/Tegath/elevedia/commit/a9854b5c5e6d30292e5702cba8e9452406810738) · `a9854b5`
  - [feat(calls): recherche full-text des transcripts sur immo, services et médecins](https://github.com/Tegath/elevedia/commit/27013de6626a0a5daf4cbbe6ad24e2aa3d11060a) · `27013de`
  - [feat(dashboard): pick reservation time in quick dialog, edit date/time on reservation sheet](https://github.com/Tegath/elevedia/commit/79be6197a63ac702ce142a5c57a449b30dfae3bc) · `79be619`
  - [fix(medecins): live RDV alerts + agenda formatting](https://github.com/Tegath/elevedia/commit/b802999b9c8fb168a6996eb5c4e9172e9e97e748) · `b802999`
  - [feat(medecins): one-time catch-up for missed notifications](https://github.com/Tegath/elevedia/commit/175dbce798b09c4c5bcb3aa9068e749f02ba464e) · `175dbce`
  - [feat(medecins): group callback requests by caller (coiffeur parity)](https://github.com/Tegath/elevedia/commit/df3a91bfcd8f8763987cb9d5dd77d570db1de42e) · `df3a91b`
  - [feat(medecins): group by caller in every inbox view](https://github.com/Tegath/elevedia/commit/502045f75ca228a4677b92b85a1d5778f8a98f9b) · `502045f`
  - [feat(medecins): inline mark-as-handled button on every inbox row](https://github.com/Tegath/elevedia/commit/5b3f2c769a8c99f696f18c10b05ccbae91ad33d0) · `5b3f2c7`
  - [feat(medecins): day/hour filters and sort in the inbox](https://github.com/Tegath/elevedia/commit/5eb850c5b67c1558c086f5f2e1c247482d2c300f) · `5eb850c`
  - [fix(ops): provider-poller — a PX fallback counts as MiniMax only when MiniMax actually spoke](https://github.com/Tegath/elevedia/commit/215da2c7d4ecf59636419454509a82ec0f4a1172) · `215da2c`
  - [feat(medecins): A rappeler / A confirmer panel above the agenda (coiffeur parity)](https://github.com/Tegath/elevedia/commit/0db91f17524d7e1e6b943b665df28d2e738baf3e) · `0db91f1`
  - [feat(medecins): urgency ranking for A confirmer rows (coiffeur parity)](https://github.com/Tegath/elevedia/commit/0b0acb02bf24a4fe4277fcef0a44c62ebbd2b0e2) · `0b0acb0`

### Ops & infrastructure

- **4 commits** · `Tegath/mission-control`
  - [feat(video): studio upgrade — musique calée, springs, multi-format, critique visuelle, shotlist](https://github.com/Tegath/mission-control/commit/fd2f007545b79f74d4141582675732639d58739a) · `fd2f007`
  - [fix(video): libre — budget de sortie 24k + concision forcée (JSON tronqué à 14k)](https://github.com/Tegath/mission-control/commit/d848277b384dfead08c1b80159033742605815c9) · `d848277`
  - [fix(video): persiste la critique verdict ok + reprise des running orphelins (worker), worker daté dans le repo](https://github.com/Tegath/mission-control/commit/be209d037cd7c413d73f2e82623c4c8e3c98ee87) · `be209d0`
  - [fix(video): mode libre sur deepseek-v4-pro — clé Anthropic à sec, V4.1 Flash tronquait le JSON (A/B 2026-10-07)](https://github.com/Tegath/mission-control/commit/40bf7a998579345eebc7d13652260dd041204972) · `40bf7a9`

### Multichannel — outreach

- **2 commits** · `Tegath/layton-multichannel`
  - [feat(tools): proxy treg's public tool catalog](https://github.com/Tegath/layton-multichannel/commit/d13a47ef47ec5d50f90212b87f761aad873e38e4) · `d13a47e`
  - [feat(dashboard): add the Outils catalog page](https://github.com/Tegath/layton-multichannel/commit/efc5efd95add26483228c587c596edd4edb8c33c) · `efc5efd`

---

## mercredi 7 octobre 2026

**25 commits sur 3 projets.**

### Elevedia — agents vocaux

- **18 commits** · `Tegath/elevedia`
  - [fix(dashboard): floor detail mode only in the plan editor (Options) — reservations stays plateau](https://github.com/Tegath/elevedia/commit/78089ddf788463e2833f910e97a46f10d1d14917) · `78089dd`
  - [feat(dashboard): floor display style saved in service_config — set in editor, applied on reservations](https://github.com/Tegath/elevedia/commit/4f1a9e556feb3e6680755cd060f5ab705afa69e2) · `4f1a9e5`
  - [feat(app-admin): provider-aware calendar-sync engine (Google + Outlook/Microsoft Graph)](https://github.com/Tegath/elevedia/commit/cb8fe562c0dfe04720a55ab3077010524219d657) · `cb8fe56`
  - [feat(app-admin): Outlook Calendar OAuth routes (tenant + member) with provider-switch cleanup](https://github.com/Tegath/elevedia/commit/12e0b7b2918708eec854c2dd5ef7276f48b7f9e5) · `12e0b7b`
  - [feat(services,notaire): connect Outlook agenda (cabinet + membre) alongside Google](https://github.com/Tegath/elevedia/commit/4f54e8776cf5cddd7e475a2689147c30d2e65876) · `4f54e87`
  - [feat(medecins): connect Outlook agenda (cabinet + praticien) alongside Google](https://github.com/Tegath/elevedia/commit/fd05979e1ca258a334c493954272d296daca3c57) · `fd05979`
  - [feat(dashboard): day panel by service sections — upcoming/seated/settled, orange arrival & red settle buttons](https://github.com/Tegath/elevedia/commit/3cb000bc0c6cd780a6199e3bbfeb0f1c035ff2dd) · `3cb000b`
  - [docs(lab-notes): stale checkout gotcha (read origin/master, not the lagging worktree)](https://github.com/Tegath/elevedia/commit/2575ee2c59a27884c435a4844ad9cbaca74fa323) · `2575ee2`
  - [feat(sms): textes SMS personnalisables par le client (resto v1)](https://github.com/Tegath/elevedia/commit/4260311229102122d82c299762c4e8be0b27ec14) · `4260311`
  - [fix(dashboard): day panel — no horizontal overflow on confirm rows, service headers only when both services exist](https://github.com/Tegath/elevedia/commit/481cc2ba2b78c94d58662a9e88ef5fd82f7853d2) · `481cc2b`
  - [feat(dashboard): reservation dialog — covers stepper (-/+) in edit mode](https://github.com/Tegath/elevedia/commit/7949d762ef8271af9792b06b90c7bcb17cc4a3a1) · `7949d76`
  - [fix(dashboard): recheck row — badge in content, full note in tooltip (compact card)](https://github.com/Tegath/elevedia/commit/ec3f2b143a85245d4fdfaf6fc25117ace0f13c50) · `ec3f2b1`
  - [feat(sms): textes personnalisables sur les 5 verticales (système flexible)](https://github.com/Tegath/elevedia/commit/825bbd8c385f93f009cccf57e4f83dd00d1cbe39) · `825bbd8`
  - [feat(sms): avertissement visible — un lien décompte 7 min au lieu de 4](https://github.com/Tegath/elevedia/commit/4ae168b7c8388a6b3c6a9cd9742f24cea5e48a7d) · `4ae168b`
  - [feat(dashboard): bar tables (4/6/8 places, wood counter + stools) and decor items (plants, banquettes, buffet) in the floor editor](https://github.com/Tegath/elevedia/commit/d97e5ffd0ea811fbd54f7e02ad21cefc751dd248) · `d97e5ff`
  - [feat(sms): SMS des nœuds de flow — visibles et personnalisables (option A+B)](https://github.com/Tegath/elevedia/commit/6a4a299bd5bdb6dbdad13abf007ca060ecc349da) · `6a4a299`
  - [feat(sms): SMS de flow visibles/éditables sur les 4 autres verticales](https://github.com/Tegath/elevedia/commit/6ecc9549fd59ce86403cb451a5d75233472b3773) · `6ecc954`
  - [feat(vitrine): variantes d'une prestation regroupées — 1 intitulé, 1 description](https://github.com/Tegath/elevedia/commit/b1f89bd1cc8c23565bd1aae99d0d9855871f5893) · `b1f89bd`
- **5 commits** · `Tegath/elevedia-web`
  - [feat(fiche): Bellinzis Marine + socle SEO local généralisé (H1/title/meta, offres, geo)](https://github.com/Tegath/elevedia-web/commit/8091c137dc76020a77ffaece5c54942b6cc202ad) · `8091c13`
  - [chore(directory): scheduled sync (client edits)](https://github.com/Tegath/elevedia-web/commit/cc34cc6795ef7ed77e7e1b15bbcfe257106d04c7) · `cc34cc6`
  - [feat(seo): socle SEO local généralisé aux verticales santé et restaurant](https://github.com/Tegath/elevedia-web/commit/c2677d966c12c29082690c5b909571c5f3b1b1c3) · `c2677d9`
  - [chore(directory): scheduled sync (client edits)](https://github.com/Tegath/elevedia-web/commit/f314ca9efcd539538b9a786c59791b7f3afdd29a) · `f314ca9`
  - [feat(fiche): variantes regroupées — une description par prestation](https://github.com/Tegath/elevedia-web/commit/b1a8f2fdac47b119c85765ce21ccf608ebf5774c) · `b1a8f2f`

### Multichannel — outreach

- **1 commit** · `Tegath/layton-multichannel`
  - [docs(agents): regle d'attribution des commits (auteur humain + trailer agent)](https://github.com/Tegath/layton-multichannel/commit/a44629677c9121644825544b917be7f9b6f44bff) · `a446296`

### Ideta Cyber

- **1 commit** · `Tegath/ideta-cyber`
  - [feat: hybrid LLM engines — local Gemma (simple-first) + Anthropic (expert-first) with cross fallback](https://github.com/Tegath/ideta-cyber/commit/128d00664b82df118bb71e3493d44c826c68baa5) · `128d006`

---

## mardi 6 octobre 2026

**1 commit.**

### Elevedia — agents vocaux

- **1 commit** · `Tegath/elevedia`
  - [feat(dashboard): detailed floor-plan mode — drawn chairs under plates, option d'affichage](https://github.com/Tegath/elevedia/commit/8f4921460f5ae2a5c0c64c05eb8fa1d782dde3aa) · `8f49214`

---

## lundi 5 octobre 2026

**21 commits.**

### Elevedia — agents vocaux

- **18 commits** · `Tegath/elevedia`
  - [fix(birth): T1.3b — specToProvisionInput laissait tomber template (custom_vars sans birth_template au 1er smoke) ; test de survie du mapper](https://github.com/Tegath/elevedia/commit/c171fe27f339b355b876ce5f50dfce59d7d30657) · `c171fe2`
  - [fix(embed): strip duplicated identity from the embedded tunnel (fiche already shows it)](https://github.com/Tegath/elevedia/commit/149e9ad1d8170b4674756f0dba590888c00b0ac0) · `149e9ad`
  - [fix(deploy): le filtre api inclut les paquets qu'il bundle (app-voice-config & co) — un fix de schéma de naissance ne redéployait jamais l'API](https://github.com/Tegath/elevedia/commit/5a299336ca5ac10c71533b3260265f1c6fd9ec0d) · `5a29933`
  - [feat(sms): vérité de livraison sur les 4 verticales + log SMS admin](https://github.com/Tegath/elevedia/commit/614940df91e8ec8c6d90ad37ea59243f06c7e292) · `614940d`
  - [feat(birth): T1.3c — le kit notaire pose aussi les flags moteur (feature_overrides fusionnés : biens, rdv_notaire, identity_full, staff_auto, info_sheets, slots_first, crm_lookup, sms_notaire_be)](https://github.com/Tegath/elevedia/commit/e4d767d4df0a8d22f4c0748bc01f3ff5e31bdc99) · `e4d767d`
  - [fix(db): NOTIFY pgrst en fin de 0029 (garde-fou migrations)](https://github.com/Tegath/elevedia/commit/571fc9f61a6ee2cad29afd95314f8ae7d58be480) · `571fc9f`
  - [fix(sms): les admins verticales lisent vraiment le registre SMS](https://github.com/Tegath/elevedia/commit/1f61b22242965e6824635b1f7003916a520d43ed) · `1f61b22`
  - [feat(sms): log admin filtrable et triable par client](https://github.com/Tegath/elevedia/commit/483e7381572de9e11d5f4687aae51e26a46418ee) · `483e738`
  - [fix(sms): réconciliation — Telnyx plafonne à 50 records, découper la fenêtre](https://github.com/Tegath/elevedia/commit/c7048c1bb0b286f29dc52c5ad6bb02bff5fddf7d) · `c7048c1`
  - [fix(sms): réconciliation — throttle + backoff 429 et fenêtre = plage en attente](https://github.com/Tegath/elevedia/commit/db4e6b21f339fd279492f098d2dc2246cb2e15a2) · `db4e6b2`
  - [fix(sms): réconciliation — retry des 5xx Telnyx (10007) et throttle 300 ms](https://github.com/Tegath/elevedia/commit/e229047dc74d2dc52ab9150c31c1dd61a55595ac) · `e229047`
  - [fix(dashboards): un hoquet d'auth ne déconnecte plus — tolérance panne portée aux 4 verticales, assets statiques hors middleware](https://github.com/Tegath/elevedia/commit/54d879452e2c0d01a616fb259af1c9cedeca398d) · `54d8794`
  - [fix(dashboards): « se déconnecter » ne révoque plus que la session courante (scope local)](https://github.com/Tegath/elevedia/commit/ea6ec5bbb77ce14b939f92cc9da63fde86652ec3) · `ea6ec5b`
  - [fix(audit): répare les grants d'exécution de insert_audit_log — « voir et agir » refusé (permission denied, 42501)](https://github.com/Tegath/elevedia/commit/f3d55576cbd5366cb458c554d732e017c136728a) · `f3d5557`
  - [feat(sms): refuser les fixes BE avant Telnyx + avertir à la saisie](https://github.com/Tegath/elevedia/commit/ca4f72b2c2bd4d095c1b9bd466b78c6ebfd35124) · `ca4f72b`
  - [feat(sentinelle): règle B4c — SMS d'alerte rejeté par l'opérateur](https://github.com/Tegath/elevedia/commit/8ad1eb7e404608372fabf39d29925dbd2acc0215) · `8ad1eb7`
  - [docs: add voice fleet architecture diagrams (PlantUML + SVG gallery)](https://github.com/Tegath/elevedia/commit/17e68c7f6e2b78ed8f30af0ff8c1627089d7d44d) · `17e68c7`
  - [docs: add S2S target architecture diagrams (deployment + turn sequence)](https://github.com/Tegath/elevedia/commit/2ce1f52c763fdf86bf402c5a094489fd406089f3) · `2ce1f52`
- **3 commits** · `Tegath/elevedia-web`
  - [fix(fiche): booking tunnel after the photo mosaic, no duplicate heading, photos label matches the vitrine](https://github.com/Tegath/elevedia-web/commit/ac2860462f4d149a91a1b9f7cb14b025a1cef237) · `ac28604`
  - [feat(directory): 5-min publish loop — sync client data and rebuild the hub only when the snapshot changed](https://github.com/Tegath/elevedia-web/commit/f9e40e63b311ea8d051fab350b0a99ea4cae9aae) · `f9e40e6`
  - [feat(agenda): hub — agenda gratuit + essai premium 30 j (rappels SMS en premium)](https://github.com/Tegath/elevedia-web/commit/0c81ca7303edc06e2a5a28bde360b2422f740523) · `0c81ca7`

---

## dimanche 4 octobre 2026

**32 commits.**

### Elevedia — agents vocaux

- **4 commits** · `Tegath/elevedia-web`
  - [fix(seo): venue meta descriptions from factual data instead of client taglines](https://github.com/Tegath/elevedia-web/commit/c5663416dbb05d17e219b3a454decc5e34b4bfad) · `c566341`
  - [perf(images): self-host hero polaroids as WebP, convert partner logos to WebP with intrinsic dims](https://github.com/Tegath/elevedia-web/commit/9b3facbe6f74963e477c1de7b361bab7c1c4152b) · `9b3facb`
  - [feat(seo): client fiches adopt the book.services design; city keywords (subtitle, chips, areaServed) + 7-day hours](https://github.com/Tegath/elevedia-web/commit/e64a039e2625cd552cc67c42b1791e3b39ff2b80) · `e64a039`
  - [feat(seo): fiche hub embeds the booking tunnel (iframe + auto-height) and publishes clients.json for cross-canonical](https://github.com/Tegath/elevedia-web/commit/00be82cc0b5793cd8de8e36c5c8a96b82bd9691f) · `00be82c`
- **28 commits** · `Tegath/elevedia`
  - [feat(crm): signed deal → onboarding intake pipe (W5)](https://github.com/Tegath/elevedia/commit/746f73021ffc6a7a09bdba048ce89cad26043684) · `746f730`
  - [feat(dashboard): pure health-triage engine for voice QA (W3 tranche 1)](https://github.com/Tegath/elevedia/commit/8a21e12df9b4367abb734581b596545dfd2f9df6) · `8a21e12`
  - [feat(dashboard): /admin/sante per-client health board (W3 tranche 1)](https://github.com/Tegath/elevedia/commit/06f7ff15eb42d48e96add10c0c484cb092f8a0bb) · `06f7ff1`
  - [feat(dashboard): W1 onboarding queue — signed→live file, cahier delta, computed go-live checklist](https://github.com/Tegath/elevedia/commit/18c8262d545c6c619d64db51ea59472ff20655a3) · `18c8262`
  - [fix(dashboard): onboarding vertical safety — alias medical, unknown never read as resto, pump-support banner](https://github.com/Tegath/elevedia/commit/a74e1251a51cc3e74df906b0102b8e1487971320) · `a74e125`
  - [fix(dashboard): sante — filter sentinel_daily by vertical, drop foreign-tenant fixes, vertical impact fallback](https://github.com/Tegath/elevedia/commit/98f202d9e0e83a96432c425df7efcab43ef0ce90) · `98f202d`
  - [feat(dashboard): persistent notification stack + live bell state (resto)](https://github.com/Tegath/elevedia/commit/5ce9832fe266c922575709fb77cac87d3cd011e4) · `5ce9832`
  - [fix(seo): services dashboard metadata — vertical-correct description, noindex auth pages, agenda-aware signup title](https://github.com/Tegath/elevedia/commit/6c4cc7f1e92097008a0db123933147645c1771ff) · `6c4cc7f`
  - [fix(seo): booking mini-site meta description includes city and action](https://github.com/Tegath/elevedia/commit/ca3ba8a901401b36d9efc8d3ca70849338cd58d1) · `ca3ba8a`
  - [fix(dashboards): service worker caches static assets only — no authenticated pages/redirects (fake logout on flaky wifi/PWA)](https://github.com/Tegath/elevedia/commit/95644cd97d8b04a316963db42d2db36efba57500) · `95644cd`
  - [fix(dashboards): exclude sw.js from auth middleware (service worker must be served from root, was 307 to /login)](https://github.com/Tegath/elevedia/commit/5c504a421c4893ddb7152323fde712b89e80426e) · `5c504a4`
  - [feat(seo): medecins booking site — canonical/JSON-LD/sitemap + public directory endpoint](https://github.com/Tegath/elevedia/commit/8b050f1eb6e0ece36539e9bd92208312267c485e) · `8b050f1`
  - [feat(seo): services booking site — canonical/JSON-LD/sitemap + public directory endpoint](https://github.com/Tegath/elevedia/commit/f3a960bd922eb6f9eb699892103137807d16e676) · `f3a960b`
  - [feat(seo): indexable mini-sites — shared canonical/JSON-LD layer + resto ordering site](https://github.com/Tegath/elevedia/commit/45355f4b468337b514c245c22c78a4680953fd19) · `45355f4`
  - [fix(site-builder): noUncheckedIndexedAccess in hours spec test](https://github.com/Tegath/elevedia/commit/6981620577fc6e1ee7919baa93f9f9186488f861) · `6981620`
  - [fix(seo): exclude demo/lab tenants from mini-site directory endpoints](https://github.com/Tegath/elevedia/commit/da2dfa8426e18f576a152ade837b36c9774bf93b) · `da2dfa8`
  - [fix(seo): sitemaps refresh every 5 min instead of caching the first render for 1h](https://github.com/Tegath/elevedia/commit/1cd9e0262cfcb1a785d577bba9a0b4a43faf1621) · `1cd9e02`
  - [fix(build): self-host booking-site fonts with next/font/local — kills the Google Fonts CI flake](https://github.com/Tegath/elevedia/commit/19bde733a02e8cc97c15a067e9320be3d5abc386) · `19bde73`
  - [fix(seo): normalize legacy clinic hours + strip stray paren from ecocup booking slug (applied)](https://github.com/Tegath/elevedia/commit/91e2ff03cbe26e3b340c2851f3187ba0fb1e7ff5) · `91e2ff0`
  - [fix(build): unquoted object keys in generated local-font sources (Turbopack)](https://github.com/Tegath/elevedia/commit/5f4c0b6b76aa3271353110010b23771ad80d8d18) · `5f4c0b6`
  - [fix(app-auth): single-flight session refresh in shared middleware (one refresh per cookie, prevents token-family revocation)](https://github.com/Tegath/elevedia/commit/c413677af20dd9ff6d2729f17645692414b9a1ca) · `c413677`
  - [feat(immo): migrate dashboard to self-hosted Supabase (db-immo.elevedia.be)](https://github.com/Tegath/elevedia/commit/12a1398a9802956ad77c896b33484d820bd0a780) · `12a1398`
  - [feat(seo): hub fiche embeds the booking tunnel — /embed proxy (no chrome), hub-canonical consolidation via clients.json, embed excluded from robots/sitemaps](https://github.com/Tegath/elevedia/commit/01c34158b5f29c2378061304cb484379cfb64cb3) · `01c3415`
  - [feat(birth): T1.3 — une étude naît complète : template notaire hérité (birth_template), type sobre + catalogue des 9 actes par défaut, note si fiche Notaire absente](https://github.com/Tegath/elevedia/commit/7ddb7906028fed00e44201c1255d52068f77d518) · `7ddb790`
  - [feat(services-dashboard): admin go-live page (5-step rail parity)](https://github.com/Tegath/elevedia/commit/e6b5a5e8e38b151da73860327390dbcfcb0911d5) · `e6b5a5e`
  - [feat(immo-dashboard): admin go-live page (5-step rail parity)](https://github.com/Tegath/elevedia/commit/853e40baec183e43d720800e989c667c715a36a2) · `853e40b`
  - [feat(notaire-dashboard): admin go-live page (5-step rail parity)](https://github.com/Tegath/elevedia/commit/5933685d59971d5efb335260261681c7845c8581) · `5933685`
  - [feat(medecins-dashboard): admin go-live page (5-step rail parity)](https://github.com/Tegath/elevedia/commit/ded5d03e107a39f71103907dc7a2d0f80642a0c1) · `ded5d03`

---

## samedi 3 octobre 2026

**2 commits.**

### Elevedia — agents vocaux

- **2 commits** · `Tegath/elevedia`
  - [fix(db): accept_reservation skips covers capacity in table mode](https://github.com/Tegath/elevedia/commit/297416b2e6308d896741ea07ed3aa8b2bb1bc3a0) · `297416b`
  - [feat(api): /internal/available-slots — list free resto slots (TECH-20)](https://github.com/Tegath/elevedia/commit/b03bb8d23bf130c3e01282f6b7964f6d81af8dba) · `b03bb8d`

---

## vendredi 2 octobre 2026

**17 commits.**

### Elevedia — agents vocaux

- **5 commits** · `Tegath/elevedia-web`
  - [feat(seo): client directory — public pages /sante/<cabinet> and /services/<etablissement>](https://github.com/Tegath/elevedia-web/commit/bc791c8f926a2447f3b28ab17ab18657ceebe28c) · `bc791c8`
  - [feat(seo): restaurant directory — /restaurant/<slug> + /restaurant/adresses/ (Baba, Baalbeck)](https://github.com/Tegath/elevedia-web/commit/08dce48b8e99efc5f2dc9750a750a407fad7df68) · `08dce48`
  - [feat(seo): richer venue schema — priceRange, servesCuisine, hasMenu, ReserveAction](https://github.com/Tegath/elevedia-web/commit/7adad548ab91a86bd094ac14e8820af7bbc6d5d6) · `7adad54`
  - [feat(offer): agenda-only page /services/agenda/ — 20 €/mo, 1 week free, signup CTA (?produit=agenda) + landing banner](https://github.com/Tegath/elevedia-web/commit/c2379523405e6e87097ea58ebe8c8ee908a09bcb) · `c237952`
  - [fix(seo): sync-directory fails fast + idempotent; honest agenda offer copy](https://github.com/Tegath/elevedia-web/commit/ad5f3cbb8c809356880e4b79ba978d04b13f3280) · `ad5f3cb`
- **12 commits** · `Tegath/elevedia`
  - [feat(voices): 7 more Gradium voices, recommended on every vertical](https://github.com/Tegath/elevedia/commit/2eae1a292c8c8afb4c549e536908e701fc6a2abd) · `2eae1a2`
  - [fix(medecins-dashboard): call_turns legacy FK — turns and console metrics were empty](https://github.com/Tegath/elevedia/commit/0abd98d87bd913ed3cb892f2699d2c0fb96573c0) · `0abd98d`
  - [feat(services): agenda-only pilot — signup path, 7-day trial, locked voice features](https://github.com/Tegath/elevedia/commit/cbde49b94dff2d7e140ba186e9884d37d7e401e4) · `cbde49b`
  - [fix(services): render the signup form server-side with ?produit read by the page](https://github.com/Tegath/elevedia/commit/bb50d66aad905b91270cd209bffb419760068b61) · `bb50d66`
  - [feat(services): Stripe checkout for the agenda plan (20€/mo, trial end = free week)](https://github.com/Tegath/elevedia/commit/d05493e43b36a02d8d743f67cf877bfdd9a5fd41) · `d05493e`
  - [fix(services): await createClient() in agenda checkout action](https://github.com/Tegath/elevedia/commit/c7251be6d99814a33826ace3a768de947ac93bef) · `c7251be`
  - [feat(services): agenda trial banner — free week visible, soft block when expired (CTA -> /plan)](https://github.com/Tegath/elevedia/commit/2fa8643cd38a5aa10f7a8a85607f1cf30b703ced) · `2fa8643`
  - [feat(observability): show backchannel + tool_filler markers on the call timeline](https://github.com/Tegath/elevedia/commit/27a40b35e22cfceb1a8ed6ef28d5cba788ae6a32) · `27a40b3`
  - [fix(services): harden the agenda pilot (audit pass 1)](https://github.com/Tegath/elevedia/commit/0214a7e2275629355594e65f01e95dcf4feb4340) · `0214a7e`
  - [test(app-billing): align cancellation notification expectation with the neutral copy](https://github.com/Tegath/elevedia/commit/fcb6cb9d56ba6d5cda720a5b5388bd2bd0f89607) · `fcb6cb9`
  - [feat(services): agenda trial reminders + audit follow-ups](https://github.com/Tegath/elevedia/commit/b7f10f71ac35ce39f289ce73b6c1f5703df892c3) · `b7f10f7`
  - [feat(site): Elevedia brand template per vertical (matches elevedia.be identities)](https://github.com/Tegath/elevedia/commit/27c59a6b088708bdbb9a739b1772b333b4a88c05) · `27c59a6`

---

## jeudi 1 octobre 2026

**8 PR fusionnées, 8 PR ouvertes et 22 commits.**

### Elevedia — agents vocaux

- **PR fusionnée** · [feat(resto): dashboard P1 — tickets de table, clients, appels](https://github.com/Tegath/elevedia/pull/653) · `Tegath/elevedia`
- **PR fusionnée** · [feat(conductor): Réglages resto — les choix client pilotent le flow golden (v2)](https://github.com/Tegath/elevedia/pull/654) · `Tegath/elevedia`
- **1 commit** · `Tegath/elevedia-web`
  - [feat(cgv): publish CGV v5.1 (21 septembre 2026)](https://github.com/Tegath/elevedia-web/commit/b8751828ef8260a2230adc2834b88a226b0877ca) · `b875182`
- **PR fusionnée** · [feat(medecins): liste d'attente gatée par la clé catalogue medecins.waitlist.enabled](https://github.com/Tegath/elevedia/pull/655) · `Tegath/elevedia`
- **PR fusionnée** · [feat(assistant): l'assistant self-serve du restaurateur — chat d'abord, garde-fous intacts](https://github.com/Tegath/elevedia/pull/656) · `Tegath/elevedia`
- **PR fusionnée** · [feat(medecins): consignes pré-examen par acte (CIM² v1)](https://github.com/Tegath/elevedia/pull/657) · `Tegath/elevedia`
- **21 commits** · `Tegath/elevedia`
  - [feat(resto): dashboard P1 — tickets de table, clients, appels (#653)](https://github.com/Tegath/elevedia/commit/a33a82074e8c67d9d2f56db5f4b5c791bc0cfa85) · `a33a820`
  - [feat(conductor): Réglages resto — les choix client pilotent le flow golden (v2) (#654)](https://github.com/Tegath/elevedia/commit/ba2a6a05219e87bc345b3058f1f239e12f516503) · `ba2a6a0`
  - [feat(notaire-dashboard): biens — 3 statuts (À vendre / En attente de signature / Retiré)](https://github.com/Tegath/elevedia/commit/ed1cef800804c0607b59fedf1107a98979364e89) · `ed1cef8`
  - [feat(medecins): gate the waitlist behind medecins.waitlist.enabled (#655)](https://github.com/Tegath/elevedia/commit/c5a3f231dab025c1a360e34f03d9274756fa303d) · `c5a3f23`
  - [feat(assistant): l'assistant self-serve du restaurateur — chat d'abord, garde-fous intacts (#656)](https://github.com/Tegath/elevedia/commit/adf553046b9c97390a66a30d312dea5aa3d19af9) · `adf5530`
  - [feat(medecins): test de renvoi Telnyx sur la fiche agent + service test-call local](https://github.com/Tegath/elevedia/commit/323b6c0688672a2b56039353b2672b6eeace2cf7) · `323b6c0`
  - [feat(features): catalogue — emporter_transfert + transfer_night_gate (golden v4.6/v4.7)](https://github.com/Tegath/elevedia/commit/29c1761cad24bc7c90ebb552e77e4d4ddae1b1ee) · `29c1761`
  - [ops(birth): birth-smoke-medecins delete — supprime un tenant de banc et son compte](https://github.com/Tegath/elevedia/commit/f06284efd2933d7896ce87e50e5b5031d4c24060) · `f06284e`
  - [feat(medecins): test de transfert — appel réel depuis la ligne de l'agent (AMD) + verdict humain/messagerie](https://github.com/Tegath/elevedia/commit/61c7691d8df8c3285f3069bdcabc5008985c1c9c) · `61c7691`
  - [feat(medecins): consignes pré-examen par acte (CIM² v1) (#657)](https://github.com/Tegath/elevedia/commit/7291d468a2add58479f55020ada53d7ffa900ca9) · `7291d46`
  - [feat(medecins): le RDV porte l'acte (appointments.prestation_id) (#658)](https://github.com/Tegath/elevedia/commit/c6d5c5ea922cde18c889a8b1b12e0efc743b5869) · `c6d5c5e`
  - [feat(assistant): capacités bornées, prompt client, verdict du run + montage services (#659)](https://github.com/Tegath/elevedia/commit/9b153953dc1f499c293f569d345655bc72d39414) · `9b15395`
  - [feat(dashboard): « Voir l'appel » ouvre la transcription en pop-up depuis Commandes](https://github.com/Tegath/elevedia/commit/90a49461b040f383a79d9085d7ca5a9f3a2d887e) · `90a4946`
  - [fix(immo): notification emails target the immo app and read NEXT_PUBLIC_APP_URL](https://github.com/Tegath/elevedia/commit/e2d0cb5a065dc25731d5edfe65f2a10b49cbaba0) · `e2d0cb5`
  - [fix(dashboard): derive dashboard URL from env](https://github.com/Tegath/elevedia/commit/94f62455244175417ab0625e59e4ff479dbab54d) · `94f6245`
  - [fix(medecins): derive dashboard and booking URLs from env](https://github.com/Tegath/elevedia/commit/aa9ec5b9024a9810d7af12ef8ac34ecd26df03a1) · `aa9ec5b`
  - [fix(services,notaire): derive dashboard and booking URLs from env](https://github.com/Tegath/elevedia/commit/d96d4216c83d02085e66e64a94074b58fe50d94f) · `d96d421`
  - [chore: fix api host typo in .env.example](https://github.com/Tegath/elevedia/commit/ff20d1da3d898869803253ee93d5e09618649d86) · `ff20d1d`
  - [ci: pass NEXT_PUBLIC_BOOKING_URL to services, notaire and medecins dashboard builds](https://github.com/Tegath/elevedia/commit/2716daa9265916c8099dbe82e1d4f4cd47095cc0) · `2716daa`
  - [fix(quality-worker): make digest dashboard link configurable via QW_DASHBOARD_URL](https://github.com/Tegath/elevedia/commit/c4d2c2980f7420af1d1b66e02148a6702195b32d) · `c4d2c29`
  - [feat(assistant): médecins + notaire montés (même coquille) (#660)](https://github.com/Tegath/elevedia/commit/94c3dc61a772094e71c8a304f38f60b4662ca38f) · `94c3dc6`
- **PR fusionnée** · [feat(medecins): appointments.prestation_id — le RDV porte l'acte (consignes voix)](https://github.com/Tegath/elevedia/pull/658) · `Tegath/elevedia`
- **PR fusionnée** · [feat(assistant): capacités bornées, prompt client, verdict du run + montage services](https://github.com/Tegath/elevedia/pull/659) · `Tegath/elevedia`
- **PR fusionnée** · [feat(assistant): médecins + notaire montés (même coquille)](https://github.com/Tegath/elevedia/pull/660) · `Tegath/elevedia`

---

## mercredi 30 septembre 2026

**4 PR fusionnées, 5 PR ouvertes et 9 commits.**

### Elevedia — agents vocaux

- **PR ouverte** · [registry(diagrammes): specs flux-appel (gabarit schémas tldraw)](https://github.com/Tegath/kb/pull/1) · `Tegath/kb`
- **PR fusionnée** · [SSI-4 — onboarding immo : étape formule + reprise au bon endroit](https://github.com/Tegath/elevedia/pull/649) · `Tegath/elevedia`
- **PR fusionnée** · [KDS Baba P1 : n° de table figé + passe bar « Plat prêt » + alertes par poste](https://github.com/Tegath/elevedia/pull/650) · `Tegath/elevedia`
- **PR fusionnée** · [feat(delegation): dashboards clients depuis demo.elevedia.be sans accès admin](https://github.com/Tegath/elevedia/pull/651) · `Tegath/elevedia`
- **9 commits** · `Tegath/elevedia`
  - [feat(ssi4): onboarding immo — etape formule + reprise au bon endroit](https://github.com/Tegath/elevedia/commit/625cee94a148994f7cc37a5f7af6432380a1da77) · `625cee9`
  - [KDS Baba P1 : n° de table figé + passe bar « Plat prêt » + alertes par poste (#650)](https://github.com/Tegath/elevedia/commit/c48f6bf0ca69a674344b895417a4878a78763b9c) · `c48f6bf`
  - [feat(transfer): end-to-end transfer test — AMD human/voicemail verdict, admin panel, migration transfer_test_*](https://github.com/Tegath/elevedia/commit/de50065be621755552a7257ffeccfd6831246306) · `de50065`
  - [feat(delegation): dashboards clients depuis demo.elevedia.be sans accès admin (#651)](https://github.com/Tegath/elevedia/commit/bb8951e163dcf4eb0d3b863aa7f7e56551a985f3) · `bb8951e`
  - [feat(api): resto births get their public booking_slug (#652)](https://github.com/Tegath/elevedia/commit/9b3857e4efedf7820df7472a7132b495f038de33) · `9b3857e`
  - [feat(sales-pwa): pastille Démos (filtre + badge) dans l'onglet Clients](https://github.com/Tegath/elevedia/commit/bc4b85cce36620d47a22bea7697a271bee063d3c) · `bc4b85c`
  - [fix(delegation): pastille Démos = les 5 démos Elevedia du site (registre webdemo + flagship resto)](https://github.com/Tegath/elevedia/commit/04af281205b6020b8ab571a01d3e13e3c9aa069f) · `04af281`
  - [feat(transfer): real post-bridge signal + client-side transfer test](https://github.com/Tegath/elevedia/commit/5f0c8603990c7cdd315ee6cf03a5984a13a78b0b) · `5f0c860`
  - [fix(transfer): TransferTestBlock props/action optionnelles — les autres dashboards (services, medecins, notaire) ne sont pas encore cables](https://github.com/Tegath/elevedia/commit/f623e1218cdf3f1c959ad66ddf8c2acb5d4c60c4) · `f623e12`
- **PR fusionnée** · [feat(api): resto births get their public booking_slug](https://github.com/Tegath/elevedia/pull/652) · `Tegath/elevedia`

---

## mardi 29 septembre 2026

**10 PR fusionnées, 10 PR ouvertes et 11 commits.**

### Elevedia — agents vocaux

- **PR fusionnée** · [feat(immo): clonage de voix + cartes voix sur la page agent (alignement phase A)](https://github.com/Tegath/elevedia/pull/639) · `Tegath/elevedia`
- **PR fusionnée** · [feat(immo): page agent alignée sur les 4 autres verticales (phase B)](https://github.com/Tegath/elevedia/pull/641) · `Tegath/elevedia`
- **PR fusionnée** · [dashboard: marquer les tours agent non prononcés (transcription)](https://github.com/Tegath/elevedia/pull/642) · `Tegath/elevedia`
- **11 commits** · `Tegath/elevedia`
  - [fix(voice): make the clone state obvious (voice card, profile, adjacency)](https://github.com/Tegath/elevedia/commit/6ba521eefffee10a909f22fad5ded5b62381a9f7) · `6ba521e`
  - [feat(immo): voice cloning + catalog voice picker on the agent page (alignment phase A) (#639)](https://github.com/Tegath/elevedia/commit/f3fc128de2df77956e1ddd6691eb0ab82fd314f9) · `f3fc128`
  - [feat(ssi1): l'essai sans carte a un prix — garde-fous test-call + un essai par telephone](https://github.com/Tegath/elevedia/commit/8aad82730dcd05911ca2ab8ebb3f89d20f6b8f34) · `8aad827`
  - [feat(immo): page agent alignée sur les 4 autres verticales (phase B) (#641)](https://github.com/Tegath/elevedia/commit/4d9678f8e5172c15abeff44b3e34c0808d329271) · `4d9678f`
  - [dashboard: marquer les tours agent non prononcés dans la transcription (#642)](https://github.com/Tegath/elevedia/commit/598025369a97852ea8bee91065e21f23a443ae06) · `5980253`
  - [feat(ssi2): checkout abonnement immo -> activation automatique (SSI-2)](https://github.com/Tegath/elevedia/commit/0f9f4dca95838c267105f1c3cf7163bf33fd8361) · `0f9f4dc`
  - [fix(birth): pass owner full_name metadata so médecins births survive the auth trigger (#644)](https://github.com/Tegath/elevedia/commit/60d071c67038767d99bd50bfbdfe75f94b06007c) · `60d071c`
  - [feat(immo): parité — colonne notifications, schéma Drizzle, garde naissance (phase C) (#643)](https://github.com/Tegath/elevedia/commit/3b3bc395a1c50b846e78dd04473822552fe8344f) · `3b3bc39`
  - [ops(birth): version the médecins birth smoke bench (#646)](https://github.com/Tegath/elevedia/commit/2abce6d5f5034b2490257cc77a3310be1b041e7d) · `2abce6d`
  - [feat(ssi3): une seule source de prix + portail self-service (immo)](https://github.com/Tegath/elevedia/commit/25b1d7600617a56ec0ca457783c5a9394d1864ba) · `25b1d76`
  - [fix(birth): la recette bloquante ne se mettait plus en file depuis le 26-09 (#647)](https://github.com/Tegath/elevedia/commit/0f81751dcbfa9e347c55eb9d8f0fec78a6961054) · `0f81751`
- **PR fusionnée** · [fix(birth): passer full_name au createUser — la naissance médecins mourait à l'étape 1](https://github.com/Tegath/elevedia/pull/644) · `Tegath/elevedia`
- **PR fusionnée** · [feat(immo): parité — colonne notifications, schéma Drizzle, garde naissance (phase C)](https://github.com/Tegath/elevedia/pull/643) · `Tegath/elevedia`
- **PR fusionnée** · [SSI-1 (v1) — essai sans carte : cap des appels test + un essai par téléphone](https://github.com/Tegath/elevedia/pull/640) · `Tegath/elevedia`
- **PR fusionnée** · [ops(birth): banc de naissance médecins versionné (smoke dev)](https://github.com/Tegath/elevedia/pull/646) · `Tegath/elevedia`
- **PR fusionnée** · [SSI-2 — checkout abonnement immo → activation automatique](https://github.com/Tegath/elevedia/pull/645) · `Tegath/elevedia`
- **PR fusionnée** · [fix(birth): la recette bloquante ne se mettait plus en file depuis le 26-09](https://github.com/Tegath/elevedia/pull/647) · `Tegath/elevedia`
- **PR fusionnée** · [SSI-3 (immo) — une seule source de prix + portail self-service](https://github.com/Tegath/elevedia/pull/648) · `Tegath/elevedia`

---

## lundi 28 septembre 2026

**2 PR fusionnées, 2 PR ouvertes et 5 commits.**

### Elevedia — agents vocaux

- **5 commits** · `Tegath/elevedia`
  - [fix(dashboard): self-heal tabs after a deploy (stale server actions)](https://github.com/Tegath/elevedia/commit/fa89bf404d8639ad50596938026bfd69ef77db06) · `fa89bf4`
  - [feat(ssi0): claim the DID at activation, not at birth (essai encadre D2)](https://github.com/Tegath/elevedia/commit/bda62a987130df55baeeeeb28b690a256e773d65) · `bda62a9`
  - [fix(ssi0): promote the claimed line out of the recyclable stock](https://github.com/Tegath/elevedia/commit/a43fa0591f80f81cb1dceb95f8cabd47ae61f731) · `a43fa05`
  - [fix(ssi0): areaPrefix becomes optional in OnboardingBirthOptions (D2 no longer uses it)](https://github.com/Tegath/elevedia/commit/4bbe7ee494ce83954e13b7294cf8cf54a5e82f74) · `4bbe7ee`
  - [feat(voice): client voice cloning via Gradium (4 dashboards) (#638)](https://github.com/Tegath/elevedia/commit/735885ed17d27e4fb714c3be166613c1e34a8f07) · `735885e`
- **PR fusionnée** · [feat(voice): clonage de voix client via Gradium (4 dashboards)](https://github.com/Tegath/elevedia/pull/638) · `Tegath/elevedia`
- **PR fusionnée** · [SSI-0 (D2) — le DID se claim à l'activation, plus à la naissance](https://github.com/Tegath/elevedia/pull/637) · `Tegath/elevedia`

---

## dimanche 27 septembre 2026

**1 PR fusionnée, 1 PR ouverte et 25 commits.**

### Elevedia — agents vocaux

- **PR fusionnée** · [feat(births): duplex_resume + registre de comportement — les naissances héritent de tous les fixes](https://github.com/Tegath/elevedia/pull/636) · `Tegath/elevedia`
- **25 commits** · `Tegath/elevedia`
  - [feat(birth): compose core+overlay and set follow_template for new resto agents](https://github.com/Tegath/elevedia/commit/e70a4f655655c92951b4ff75c1a1a4fdb809943a) · `e70a4f6`
  - [fix(api-test): languageCalls[0] possibly undefined breaks CI typecheck (noUncheckedIndexedAccess)](https://github.com/Tegath/elevedia/commit/ffbccab87778556bd5991f492f87b12ba8e3eb71) · `ffbccab`
  - [feat(dashboards): client voice picker — Gradium + MiniMax journalist, samples, 15s note](https://github.com/Tegath/elevedia/commit/c3f5a04297ee556d1a5d70ad026a92f3e4711e0f) · `c3f5a04`
  - [ci: disarm deploy-services-voice-engine (targets deprovisioned GCP L4)](https://github.com/Tegath/elevedia/commit/720956ea22afd97fbf5d881293ee55c2d014298c) · `720956e`
  - [ci: guard prod deploys to master ref + per-app concurrency](https://github.com/Tegath/elevedia/commit/8e43e6224e2c13fcedebafc6273b0429dd5b73da) · `8e43e62`
  - [docs(voice): point live ops to GEX44, drop stale root pipecat copies](https://github.com/Tegath/elevedia/commit/6e6d54467cc7ec017b39db15cd1b0382fbea3f44) · `6e6d544`
  - [chore(agent): version AGENTS.md + opencode guardrails](https://github.com/Tegath/elevedia/commit/b86fa96d71d30f332dc1500798021173c4104218) · `b86fa96`
  - [ci: ref-guard landing deploy jobs too (close dispatch path)](https://github.com/Tegath/elevedia/commit/4ac7c30ef5a48ccac723865d15418fc533cd44bb) · `4ac7c30`
  - [feat(dashboards): voice picker in two columns, gender colours, friendly avatars](https://github.com/Tegath/elevedia/commit/a742594952b48f0aa0011cc7593c08fd41291892) · `a742594`
  - [feat(dashboards): Simon's hand-picked voice avatars (9 women, Gaspard kept)](https://github.com/Tegath/elevedia/commit/0e4e1fe15f30991860c2354a03c9cf6f70446195) · `0e4e1fe`
  - [feat(dashboards): show the voice avatar next to every voice in the selectors](https://github.com/Tegath/elevedia/commit/f1da5de8bf56ba4178b836d48615018c2ec6a51d) · `f1da5de`
  - [feat(births): duplex_resume + registre de comportement — les naissances héritent de tous les fixes (#636)](https://github.com/Tegath/elevedia/commit/f8c438f422166fb7d2dd6036bfad307590b93e7b) · `f8c438f`
  - [ci(staging): take the shared host lock + ram-guard before dev deploys](https://github.com/Tegath/elevedia/commit/483c64cfda315e6ebfed2cbe028667552f696639) · `483c64c`
  - [ci: scope workflow_dispatch to a service input (no all-jobs blast)](https://github.com/Tegath/elevedia/commit/ce33888962958bd2e2999b1576b0a0f9e7288b0d) · `ce33888`
  - [ci: manual dispatch is input-only, never path-filter driven](https://github.com/Tegath/elevedia/commit/594c8822812f2d66ca37a750421e7b53235dbb0d) · `594c882`
  - [ci: test suites now gate every prod deploy](https://github.com/Tegath/elevedia/commit/b6a7c0016c7fd4ee67aa7143e5e5cd7134405ed5) · `b6a7c00`
  - [ci: pin all third-party actions to commit SHAs](https://github.com/Tegath/elevedia/commit/0c46d278226c3c0a5ba22ae99899a225b9275cb7) · `0c46d27`
  - [ci: pull by commit sha, keep :latest, wait for healthy containers](https://github.com/Tegath/elevedia/commit/8381f36ed5461c928d4f009a620d7e86e43f60d9) · `8381f36`
  - [docs(voice): livekit.yaml is L4-era — prod LiveKit runs on GEX44](https://github.com/Tegath/elevedia/commit/00b0dadc1a06e8439d73ba1cbf0aafc017f32966) · `00b0dad`
  - [ci: gate on the real suites + probe the public URL after each deploy](https://github.com/Tegath/elevedia/commit/d2caa713cb4c662759c498d73ce4d0929483f423) · `d2caa71`
  - [ci: master tests run once — the deploy gate owns them (PRs unchanged)](https://github.com/Tegath/elevedia/commit/363db9f7c4b08fb44bb06c9d0a539f105e531f69) · `363db9f`
  - [ci: weekly GHCR prune (last 10 versions per image, :latest kept)](https://github.com/Tegath/elevedia/commit/6b4749fe6468b65473d087b48062f5d269f9df4e) · `6b4749f`
  - [ci: 20m SSH budget (flock 9m + ram-guard 5m + wait 3m > the old 10m)](https://github.com/Tegath/elevedia/commit/6ec4b01a404de92858e4c7a7549f1ad87f188d75) · `6ec4b01`
  - [ci: probe the landing container directly (elevedia.be is served by the hub)](https://github.com/Tegath/elevedia/commit/9a813ebfd37c6797a310605ab079d052cc65c531) · `9a813eb`
  - [ci: least-privilege top-level permissions (jobs keep their own blocks)](https://github.com/Tegath/elevedia/commit/4c0a0b44c3eaa43cc320b9834335126ac3ef1bd5) · `4c0a0b4`

---

## samedi 26 septembre 2026

**4 PR fusionnées, 6 PR ouvertes et 11 commits sur 2 projets.**

### Elevedia — agents vocaux

- **PR fusionnée** · [fix(services): quota atteint = surconsommation comptée, jamais de pause](https://github.com/Tegath/elevedia/pull/630) · `Tegath/elevedia`
- **PR fusionnée** · [fix(services): la migration quota-overage cible consume_minutes (pas consume_new_call_minutes)](https://github.com/Tegath/elevedia/pull/631) · `Tegath/elevedia`
- **PR fusionnée** · [fix(notaire): quota atteint = surconsommation comptée, jamais de pause](https://github.com/Tegath/elevedia/pull/632) · `Tegath/elevedia`
- **PR ouverte** · [fix(sms): une relance sur 5xx/timeout — la confirmation ne part plus en fumée](https://github.com/Tegath/elevedia/pull/633) · `Tegath/elevedia`
- **PR ouverte** · [feat(quality): le juge LLM en 2e ligne de la fiche agent](https://github.com/Tegath/elevedia/pull/634) · `Tegath/elevedia`
- **10 commits** · `Tegath/elevedia`
  - [fix(services): quota atteint = surconsommation comptee, jamais de pause](https://github.com/Tegath/elevedia/commit/2ca8f05e919ec61844aea2ad6b92285e6c1e7019) · `2ca8f05`
  - [fix(services): la migration quota-overage cible consume_minutes, pas consume_new_call_minutes](https://github.com/Tegath/elevedia/commit/63676a7f926048683e7945fb09659758fa357968) · `63676a7`
  - [fix(notaire): quota atteint = surconsommation comptee, jamais de pause](https://github.com/Tegath/elevedia/commit/130f2449267d7a93ac6c5af139d7c37506dd5b49) · `130f244`
  - [fix(sms): one 1s retry on Telnyx 5xx/timeout (Jacob 9169e2d6 lost confirmation)](https://github.com/Tegath/elevedia/commit/93983a8bd41df8b2ac4856c2651b76161172a104) · `93983a8`
  - [fix(sms): reconcile the Telnyx retry with PR #633 (broader predicate, helpers)](https://github.com/Tegath/elevedia/commit/a754caa844e6f853eadb611608444d8c784e6c31) · `a754caa`
  - [feat(dashboards): one-click call languages (FR + NL/IT/EN/DE/ES/PT/AR)](https://github.com/Tegath/elevedia/commit/5bd55d0506e3fb3a0a043d0a9cfa58ba8f3137bf) · `5bd55d0`
  - [fix(birth): never cut a live agent on re-provision, require recette on the legacy path](https://github.com/Tegath/elevedia/commit/d960523563ca7b8ab29ffc207c6a2ec324ac0546) · `d960523`
  - [feat(birth): language register for spec-less births (BE = fr+nl + NL voice)](https://github.com/Tegath/elevedia/commit/fdae2546200963e0cf9cf7092114190f081ba56b) · `fdae254`
  - [fix(services-dashboard): mount the missing agent blocks on /agent](https://github.com/Tegath/elevedia/commit/1888d3aaf2ed7db514eb4f727fc08534b5d69576) · `1888d3a`
  - [docs(lab-notes): dead-file trap (#366) + local typecheck under earlyoom](https://github.com/Tegath/elevedia/commit/793372406a441274b43f72bdc4494394f3fab9b8) · `7933724`
- **PR fusionnée** · [fix(services-dashboard): parité de la page /agent avec le client resto](https://github.com/Tegath/elevedia/pull/635) · `Tegath/elevedia`

### Multichannel — outreach

- **1 commit** · `Tegath/layton-multichannel`
  - [docs(outreach): correct the SURBL listing hypothesis with forensics](https://github.com/Tegath/layton-multichannel/commit/b330446c8255da62e99fdf602bacf37324b9abb3) · `b330446`

---

## vendredi 25 septembre 2026

**6 PR fusionnées, 6 PR ouvertes et 30 commits sur 2 projets.**

### Elevedia — agents vocaux

- **PR fusionnée** · [feat(medecins): résa invité sans compte sur le site public](https://github.com/Tegath/elevedia/pull/624) · `Tegath/elevedia`
- **PR fusionnée** · [Parité admin Imovia ↔ Elevedia : agences, analytics, rapports, usage](https://github.com/Tegath/elevedia/pull/625) · `Tegath/elevedia`
- **PR fusionnée** · [Admin Imovia : page Agents vocaux (liste + fiche agent canonique)](https://github.com/Tegath/elevedia/pull/626) · `Tegath/elevedia`
- **27 commits** · `Tegath/elevedia`
  - [feat(medecins): résa invité sans compte sur le site public (#624)](https://github.com/Tegath/elevedia/commit/e48859c28e179931235b3e00341ee1bed85c5d75) · `e48859c`
  - [fix(demo): hide demo cards without menu knowledge from /demo/list and hub](https://github.com/Tegath/elevedia/commit/f4fc7b6c65e2d0a63942de773e6253c36fedafa9) · `f4fc7b6`
  - [fix(dashboard): Clients moves into the "Plus" menu, out of the top nav](https://github.com/Tegath/elevedia/commit/3216d97b30f40844dd614b2056d2a00780a6a2b2) · `3216d97`
  - [feat(api): sales demo fleet — branded Démo Elevedia restos + vertical demos](https://github.com/Tegath/elevedia/commit/2e2470a39bb3730ab2fd1b89dafe9ec4bb1f26e8) · `2e2470a`
  - [feat(sales-pwa): only Elevedia demos + recorded Gradium voices tab](https://github.com/Tegath/elevedia/commit/b9bdccacafad4abbe60cae0324039b352402a28e) · `b9bdcca`
  - [fix(sales-pwa): let voice taglines wrap instead of truncating](https://github.com/Tegath/elevedia/commit/52b11a2f38a4fa51770a5172b3337cfcb56dc436) · `52b11a2`
  - [feat(sales-pwa): add Constance + Albane (médecin/immo demo voices) to the Voix tab](https://github.com/Tegath/elevedia/commit/d390303131f3dc7bb2c8434c9764048a286152d1) · `d390303`
  - [fix(sales-pwa): wrap voice name badges so Constance is not truncated](https://github.com/Tegath/elevedia/commit/10a81aa5fe6224c3d220ae1b299aa8710f8adc9a) · `10a81aa`
  - [feat(immo-admin): agencies list parity with resto — filters, rich columns, row actions](https://github.com/Tegath/elevedia/commit/3229bfed171b00613509b194174780fc0bda446c) · `3229bfe`
  - [feat(immo-admin): analytics filters, real agent status, sortable per-agency table](https://github.com/Tegath/elevedia/commit/fb844fd0d98a863b740d1f006f9e6201ef393088) · `fb844fd`
  - [feat(immo-admin): reports — real Recharts 12-month trend (revenue/COGS/margin)](https://github.com/Tegath/elevedia/commit/c145d7665896beedfbde98057cc7533deaa5a469) · `c145d76`
  - [feat(immo-admin): usage — progress bars, quota projection, surplus margin KPI](https://github.com/Tegath/elevedia/commit/a44e4fe526119c5ba68d331f0eaa0005b8fc3851) · `a44e4fe`
  - [chore(immo-admin): /admin redirects to agencies; drop dead resto leftovers](https://github.com/Tegath/elevedia/commit/00f25fd83ca5eaa88e1ba085789083be0f0da275) · `00f25fd`
  - [feat(sales-pwa): voice samples on the fleet birth register (temp 0.8, padding -1)](https://github.com/Tegath/elevedia/commit/dcc96a3edcaaadf437f838906f252b7926b612c7) · `dcc96a3`
  - [feat(sales-pwa): colour-code feminine (teal) vs masculine (violet) voices](https://github.com/Tegath/elevedia/commit/333115d42a0343372080d475e41361f8ccc70906) · `333115d`
  - [feat(immo-admin): agents vocaux — liste dédiée + route canonique /admin/agents/[agencyId]](https://github.com/Tegath/elevedia/commit/a12701a193f3bfccaf806b408958dd8970a99959) · `a12701a`
  - [feat(sales-pwa): bilingual FR/NL badge, scripted phrase and recorded excerpt](https://github.com/Tegath/elevedia/commit/55910f6a629d34f24bcd9384dc6f75e39821b1f9) · `55910f6`
  - [feat(api): expose demo agents' call languages (bilingual FR/NL badge)](https://github.com/Tegath/elevedia/commit/2db98675ae244d4f0c396f4a27e303db1117c229) · `2db9867`
  - [feat(sales-pwa): bilingual excerpt with a male Gradium caller (FR) + male Dutch voice (NL)](https://github.com/Tegath/elevedia/commit/4e828a0c6d344a39fdaa8b56f2d9911523ba7826) · `4e828a0`
  - [feat(birth): default voice for newborn agents becomes Gradium Romane](https://github.com/Tegath/elevedia/commit/0521b8cd33c6b5fb7297afd739f20b805a934d1c) · `0521b8c`
  - [feat(sales-pwa): multilingual card FR/NL/IT with a second recorded excerpt (Italian)](https://github.com/Tegath/elevedia/commit/7cf9446e0d42e3ca9337ae33b76e9c66244064d2) · `7cf9446`
  - [services(agent): edit per-collaborator transfer numbers (businesses.transfer_targets)](https://github.com/Tegath/elevedia/commit/991aeffd7ef02b22e93a2e15ced332e718a774fe) · `991aeff`
  - [feat(sales-pwa): add the Italian bilingual excerpt asset (missed in the previous commit)](https://github.com/Tegath/elevedia/commit/758625ba3ad4cd6eb858d53128c41c0770875095) · `758625b`
  - [fix(immo-numbers): keep agencies.telnyx_phone_number + phone_numbers.agency_id in sync on assign/release](https://github.com/Tegath/elevedia/commit/1e197ca5af4f86f9122225901470d0248ad7556e) · `1e197ca`
  - [feat(immo-admin): agent page — numéro assignable + horaires d'ouverture; liste avec template](https://github.com/Tegath/elevedia/commit/dc68fd9d1c026a2b45632b5bbc2b74390838f28d) · `dc68fd9`
  - [fix(immo-numbers): garde de routage du pool + badge incohérence; nettoyage du numéro Baalbeck](https://github.com/Tegath/elevedia/commit/46a4898d8e47a5fe339891769b9d672f7bf7e67a) · `46a4898`
  - [fix(immo-numbers): garde-fou pool basé sur le trunk LiveKit (pas la connexion Telnyx) + fail-closed; connexion Telnyx active](https://github.com/Tegath/elevedia/commit/bdcf617f45311140a78151d63e508cf6b101252a) · `bdcf617`
- **PR fusionnée** · [Admin Imovia — vérif agents : bug sync numéros, numéro assignable, horaires d'ouverture](https://github.com/Tegath/elevedia/pull/627) · `Tegath/elevedia`
- **PR fusionnée** · [Admin Imovia — garde-fou numéros : le pool ne peut plus voler un numéro d'une autre verticale](https://github.com/Tegath/elevedia/pull/628) · `Tegath/elevedia`
- **PR fusionnée** · [HOTFIX — garde-fou pool : basé sur le trunk LiveKit, pas la connexion Telnyx](https://github.com/Tegath/elevedia/pull/629) · `Tegath/elevedia`

### Multichannel — outreach

- **3 commits** · `Tegath/layton-multichannel`
  - [docs(outreach): add 2026 deliverability playbook + fleet factory tooling](https://github.com/Tegath/layton-multichannel/commit/53bf02f47f4a316bedf2efe9de58887ea741bc53) · `53bf02f`
  - [feat(dashboard): add playbook page for outreach doctrine](https://github.com/Tegath/layton-multichannel/commit/17fd79983613616e4935a1b743eac092b482d1db) · `17fd799`
  - [docs(outreach): add public positions of vendors and pros (Sept 2026)](https://github.com/Tegath/layton-multichannel/commit/d9299f28778e069aa8de3396e566ae467062a734) · `d9299f2`

---

## jeudi 24 septembre 2026

**2 PR ouvertes.**

### Elevedia — agents vocaux

- **PR ouverte** · [feat(crm): variable {{outil}} dans l'outreach (plateforme métier détectée)](https://github.com/Tegath/elevedia/pull/622) · `Tegath/elevedia`
- **PR ouverte** · [feat(db): crm_directory_plateformes — plateformes métier des fiches (détection, annuaires, file)](https://github.com/Tegath/elevedia/pull/623) · `Tegath/elevedia`

---

## mercredi 23 septembre 2026

**13 PR fusionnées, 14 PR ouvertes et 46 commits sur 4 projets.**

### Elevedia — agents vocaux

- **PR ouverte** · [security(db): lock down users, definer functions, RLS (migrations NOT applied)](https://github.com/Tegath/elevedia/pull/610) · `Tegath/elevedia`
- **PR fusionnée** · [security: lock admin server actions + app_metadata role checks](https://github.com/Tegath/elevedia/pull/612) · `Tegath/elevedia`
- **PR fusionnée** · [security: backend fixes (Mollie, SMS pumping, SSRF, IDOR, fail-closed crons)](https://github.com/Tegath/elevedia/pull/611) · `Tegath/elevedia`
- **PR fusionnée** · [security(crm): app_metadata roles + ownership checks](https://github.com/Tegath/elevedia/pull/609) · `Tegath/elevedia`
- **PR fusionnée** · [security: OAuth callbacks, immo roles, fail-closed crons, tenant filters](https://github.com/Tegath/elevedia/pull/613) · `Tegath/elevedia`
- **PR fusionnée** · [fix(security): public booking limits, customer no-overwrite, server-proven onboarding phone](https://github.com/Tegath/elevedia/pull/614) · `Tegath/elevedia`
- **PR fusionnée** · [dashboard: touch-first pass (tablette, doigts, mots simples)](https://github.com/Tegath/elevedia/pull/615) · `Tegath/elevedia`
- **PR fusionnée** · [feat(births): nouveaux agents nés avec la voix Cartesia Inès](https://github.com/Tegath/elevedia/pull/616) · `Tegath/elevedia`
- **PR fusionnée** · [fix(eats-api): cap anonymous order creation (anti SMS/email/kitchen abuse)](https://github.com/Tegath/elevedia/pull/617) · `Tegath/elevedia`
- **PR fusionnée** · [sec: CRM gcal OAuth state signing, .env ignore, sharp 0.35.4](https://github.com/Tegath/elevedia/pull/618) · `Tegath/elevedia`
- **PR fusionnée** · [fix(births): close birth parity gaps (immo admin wizard, notaire golden, fr+nl, demos)](https://github.com/Tegath/elevedia/pull/619) · `Tegath/elevedia`
- **PR fusionnée** · [sec: invisible anti-bot guard on public forms + medecins signup limits](https://github.com/Tegath/elevedia/pull/620) · `Tegath/elevedia`
- **PR fusionnée** · [feat(providers): Cartesia credit tracking + premium-voice fallback alert](https://github.com/Tegath/elevedia/pull/621) · `Tegath/elevedia`
- **21 commits** · `Tegath/elevedia`
  - [feat(dashboard): restaurant recurring-client base (/clients) (#608)](https://github.com/Tegath/elevedia/commit/06664a3d6e3600d95571f2dc6e6a4dea44b238c2) · `06664a3`
  - [feat(immo-dashboard): recurring contacts base (one person, N leads/visits) (#606)](https://github.com/Tegath/elevedia/commit/a29e19f651b9046f149a1cfc3bf0da61b8db364d) · `a29e19f`
  - [security: lock admin server actions + app_metadata role checks (#612)](https://github.com/Tegath/elevedia/commit/fac27608c15cde00e99a8fd0dbeabd73c9593d22) · `fac2760`
  - [security: backend fixes (Mollie, SMS pumping, SSRF, IDOR, fail-closed crons) (#611)](https://github.com/Tegath/elevedia/commit/c8ef1f74f214f832d769d7ba0c7b9a0daa62842b) · `c8ef1f7`
  - [security(crm): app_metadata roles + ownership checks (#609)](https://github.com/Tegath/elevedia/commit/cc98d03f4ef08427edf236e2fafb52dc141ae384) · `cc98d03`
  - [security: OAuth callbacks, immo roles, fail-closed crons, tenant filters (#613)](https://github.com/Tegath/elevedia/commit/1099176cd0db9d7d00e6225888edc1a4e63ac882) · `1099176`
  - [chore(dashboard): drop real Supabase keys from .env.local.example](https://github.com/Tegath/elevedia/commit/1cc1074847d8467a75d86c43e6038772eec5cdad) · `1cc1074`
  - [chore(voice-engine): drop dead LiveKit key pair and old Redis password from repo files](https://github.com/Tegath/elevedia/commit/c9041ca8a0f7074f40dfbd6f6dadad52fde8c3c6) · `c9041ca`
  - [fix(security): public booking limits, customer no-overwrite, server-proven onboarding phone (#614)](https://github.com/Tegath/elevedia/commit/0e3f4d0d17565b5f795ca8ade930ad63a5933987) · `0e3f4d0`
  - [dashboard: touch-first pass (tablette, doigts, mots simples) (#615)](https://github.com/Tegath/elevedia/commit/23e68908ee930ca26bd5b65cd4912b3f9f62d8b5) · `23e6890`
  - [feat(births): new agents are born with the Cartesia voice Inès, not MiniMax (#616)](https://github.com/Tegath/elevedia/commit/62e7551fd6a6400a50ce60ef059df121652cefe0) · `62e7551`
  - [fix(eats-api): cap anonymous order creation (anti SMS/email/kitchen abuse) (#617)](https://github.com/Tegath/elevedia/commit/ea2a311bf6023a18be6d0d2033218f37b964bd81) · `ea2a311`
  - [sec: CRM gcal OAuth state signing, .env ignore, sharp 0.35.4 (#618)](https://github.com/Tegath/elevedia/commit/deab5c0127aec5e81078aa9c3cbb095e38731a51) · `deab5c0`
  - [fix(births): close birth parity gaps (immo admin wizard, notaire golden, fr+nl, demos) (#619)](https://github.com/Tegath/elevedia/commit/d3d550fce47a4e6e1f6ef4f3e09091e6758ccce6) · `d3d550f`
  - [fix(dashboard): /content reads hours from /agent, stops overwriting agent vars](https://github.com/Tegath/elevedia/commit/bce3cfbb073ebfa5888e7fe34de83286deb941ce) · `bce3cfb`
  - [sec: invisible anti-bot guard on public forms + medecins signup limits (#620)](https://github.com/Tegath/elevedia/commit/7a0855db9dcd5a06d3d2b35aa9a1110c77ae7916) · `7a0855d`
  - [feat(providers): track Cartesia credits and page on premium-voice fallback (#621)](https://github.com/Tegath/elevedia/commit/22272484dd3ba3b9f4e2ef80e14f541303ff36ac) · `2227248`
  - [fix(dashboard): reservations day grid back to 3 rows per quarter hour](https://github.com/Tegath/elevedia/commit/edfb47e1bd4fc80f04132dfef6f9b8229ec5f893) · `edfb47e`
  - [fix(dashboard): reservations day column no longer overflows on tablet](https://github.com/Tegath/elevedia/commit/4aa6d79bdcdb04169e4d5ad69eee9758d31cbc19) · `4aa6d79`
  - [feat(voices): add Gradium Maëlys, Lilou, Albane, Clara, Constance to voice pickers](https://github.com/Tegath/elevedia/commit/ed4f7a8e65e459a51a0cafaa7e4a1edd4d474a4e) · `ed4f7a8`
  - [feat(notaire-dashboard): fiche du bien — informations du propriétaire (nom, prénom, téléphone, email, date de naissance)](https://github.com/Tegath/elevedia/commit/d4c1141432945038759b9caec1fab5b0d1bc865a) · `d4c1141`

### Ops & infrastructure

- **1 commit** · `Tegath/docker-ops-sources`
  - [Initial import of own sources living only in /docker (map, hermes/mcp-bridge, rembg)](https://github.com/Tegath/docker-ops-sources/commit/762ce42878469633af374d4cdd51869e139d12db) · `762ce42`
- **18 commits** · `Tegath/mission-control`
  - [video: two fixed pro formats (missed calls, live call) with SFX and real voices](https://github.com/Tegath/mission-control/commit/0430e7a4806d6ba693b0ecac8d59e1a1bb7b2dc4) · `0430e7a`
  - [video formats: vouvoiement on end card, present-tense hook, coherent SMS day](https://github.com/Tegath/mission-control/commit/6e03e0d997ddda3c7a30126322eec20d78ce787d) · `6e03e0d`
  - [video formats: raise hook above caller header in live-call format](https://github.com/Tegath/mission-control/commit/8e2297ee5b6dbcf3c2699125b5cdb688a2d476a1) · `8e2297e`
  - [video: screenshots never scroll inside their frame, logo shown as-is on transparent background](https://github.com/Tegath/mission-control/commit/de91a505dc6f5b997874e291ba4acdf0b9572589) · `de91a50`
  - [video: voices from the phone agent (Cartesia) — demo agent voice for AI + narration, French caller voice](https://github.com/Tegath/mission-control/commit/8f610452542a1b75ac6f427908e1dcdb657bc073) · `8f61045`
  - [video: France-French caller voice (Marc read as Québécois)](https://github.com/Tegath/mission-control/commit/8616ffc6c8b71341b067a7becb40a243b3703966) · `8616ffc`
  - [feat(video): kit bank — fixed formats dressed per filiale, versioned](https://github.com/Tegath/mission-control/commit/9ec0d004bcb9aac1df6f85c9b28507c39cd5fe63) · `9ec0d00`
  - [fix(audit): task.updated stores only changed fields, not full task snapshots](https://github.com/Tegath/mission-control/commit/710946f6e6454192766a5b85f36c8b18895ca603) · `710946f`
  - [fix(audit): store list fields as added/removed in task.updated diffs](https://github.com/Tegath/mission-control/commit/2c62f795570b9c26bce4bda11b279b0cfce29bfc) · `2c62f79`
  - [feat(video): topic bank — one idea told by every kit × format, 'Produire' fills the missing cells](https://github.com/Tegath/mission-control/commit/e8c62cdbab9988b9d78ca88e909a13e8ecd2fe37) · `e8c62cd`
  - [fix(video): topic grid reconciles in-flight jobs with the worker's markers](https://github.com/Tegath/mission-control/commit/6012e69a059ebbd0f3e7dcb74cd38cb9a4d0beaa) · `6012e69`
  - [feat(videos): trend engine — outlier posts become reusable templates](https://github.com/Tegath/mission-control/commit/adbe0d2e5a1336e041d8924afc37aa45fb65815d) · `adbe0d2`
  - [fix(trends): accounts in error retry after 2 h, not the full interval](https://github.com/Tegath/mission-control/commit/9571c694401fe1399ffbe963b5d46f46cf8052d4) · `9571c69`
  - [feat(trends): watch the original post in the platform's own embedded player](https://github.com/Tegath/mission-control/commit/3fa22bbca054837d269d62abd8d392e9fea1f100) · `3fa22bb`
  - [feat(content): self-review loop before human review + corrections become lessons](https://github.com/Tegath/mission-control/commit/1015a4c4bb3b08be64d7b714494ad01e222ac55b) · `1015a4c`
  - [fix(tendances): drop TikTok autoplay, it makes the embedded player fail](https://github.com/Tegath/mission-control/commit/f47426fcbbdff23098b37a9fb29121f84d735ffa) · `f47426f`
  - [fix(tendances): show a fallback when a blocker removes the TikTok player](https://github.com/Tegath/mission-control/commit/4572cacfb61c2d559c490dc573c69e4c74fff0d9) · `4572cac`
  - [fix(tendances): missing still answers 204, not 404 (fail2ban banned the viewer)](https://github.com/Tegath/mission-control/commit/338f9f7116e6ff8e79c5f65a220192f81e7e4543) · `338f9f7`

### Multichannel — outreach

- **5 commits** · `Tegath/layton-multichannel`
  - [style(dashboard): tighter step editor text (14px, 24px lines)](https://github.com/Tegath/layton-multichannel/commit/60354f1392ae0136e68ecc0bd9f1e7e8e56db13a) · `60354f1`
  - [fix(sending): remove five limiters that silently stalled outreach](https://github.com/Tegath/layton-multichannel/commit/1036a935d2f357518809686e45f2f856775a66df) · `1036a93`
  - [fix(sending): broken domains, quarantine, Gmail window, DNC slots](https://github.com/Tegath/layton-multichannel/commit/f9ccf6fb6b308d43be8b3f7b2632ad41e56d439b) · `f9ccf6f`
  - [fix(tasks): Singleton retries were silently dropped](https://github.com/Tegath/layton-multichannel/commit/895a0a57b4566f2ddd5fe58b008d7299248f7f50) · `895a0a5`
  - [fix(inbox): never ingest our own mail as a prospect reply](https://github.com/Tegath/layton-multichannel/commit/2b2767a3b11943466c7b2d99307acae2ae3d6128) · `2b2767a`
- **PR fusionnée** · [fix(inbox): never ingest our own mail as a prospect reply](https://github.com/Tegath/layton-multichannel/pull/10) · `Tegath/layton-multichannel`

### Momentum OS

- **1 commit** · `Tegath/momentumos-mobile`
  - [Initial import of momentumos-mobile for off-site backup](https://github.com/Tegath/momentumos-mobile/commit/96c3c88a22d32058de64c5b78ce84d9b5a81f7be) · `96c3c88`

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
