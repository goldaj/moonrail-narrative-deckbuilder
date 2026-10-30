# Audit contradictoire / passation du 30 octobre 2026 — goldaj/moonrail-narrative-deckbuilder

Source : branches, PR et arborescence GitHub ; tests et gameplay non exécutés.

## Branches
Branche principale `main` : `dea28a3cef30337bf16e676a0bd38bfebe250c1b`.
- `chatgpt/review-20261024` : `behind`, 0 commits exclusifs, 1 commits de retard. Historique absorbé ; retirer après contrôle des usages GitHub.

## PR historiques
- [#1](https://github.com/goldaj/moonrail-narrative-deckbuilder/pull/1) — closed, fusionnée : [ChatGPT] Moonrail : sauvegarde portable de la progression et serveur local sécurisé

## Structure observée
`.gitattributes`, `.github`, `.gitignore`, `AGENTS.md`, `AUDIT_MARCHE_ET_ROADMAP.md`, `AUDIT_PRODUIT_JOUEUR.md`, `DOSSIER_PRODUIT_PRIVE_MOONRAIL.md`, `LANCER_MOONRAIL.bat`, `Lancer Moonrail.vbs`, `README.md`, `REFONTE_CENTIEME_NUIT.md`, `USER_STORIES_STATUS.md`, `app`, `assets`, `data`, `docs`, `main.py`, `serve.py`, `tests`, `tools`.

## Contre-questions fonctionnelles à tester
1. Tester un cycle complet de deckbuilding : combat, récompense, sauvegarde/rechargement et progression narrative.
2. Contrôler équilibrage : tempo, difficulté croissante, mains mortes et cas limites de cartes.
3. Vérifier les formats de sauvegarde et la portabilité sur navigateur et exécution locale.
4. Examiner la CI/les scripts, exécuter tests et partie manuelle avant certification ; aucune preuve de test nouveau n'est fournie par cette revue.
5. Conserver les branches de référence, éviter les PR redondantes, rattacher les preuves et les défauts observés au prochain commit.
