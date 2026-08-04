---
tags:
  - maths/premiere-bac-pro
  - sciences/premiere-bac-pro
  - moc
---

# Sommaire — Première Bac Pro

Ce vault regroupe le cours de **Mathématiques** et de **Sciences physiques et chimiques** de Première Bac Pro. Seul le cours proprement dit est repris ici — les évaluations (CCF, contrôles, corrigés) font l'objet d'un travail séparé, dans un autre dossier.

## Mathématiques

### Chapitres

0. [[Maths-00 Tableau des compétences]]
1. [[Maths-01 Statistiques à deux variables]]
2. [[Maths-02 Suites numériques]]
3. [[Maths-03 Fonctions — Généralités]]
4. [[Maths-04 Probabilités]]
5. [[Maths-05 Second degré]]
6. [[Maths-06 Fonctions de référence]]
7. [[Maths-07 Polynôme du second degré]]
8. [[Maths-08 Manipulation de pourcentages]]

### Fiches méthode

- [[Maths-Fiche Fonction inverse]]
- [[Maths-Fiche Inéquations]]
- [[Maths-Fiche Python — La boucle While]]
- [[Maths-Fiche Python — Exercices supplémentaires]]

## Sciences

### Chapitres

1. [[Sciences-01 Puissance et énergie électrique]]
2. [[Sciences-02 Masse volumique]]
3. [[Sciences-03 Caractériser quantitativement une solution]]
4. [[Sciences-04 Prévoir une réaction d'oxydoréduction et protéger les métaux contre la corrosion]]
5. [[Sciences-05 Oxydoréduction et protection contre la corrosion]] *(séance complémentaire à la précédente, plus développée : couples Ox/Red, demi-équations)*

### Fiches méthode

- [[Sciences-Fiche Conversions]]
- [[Sciences-Fiche Dissolution et Dilution]]
- [[Sciences-Fiche Séance de reprise — Oxydoréduction]]

---

Vue tout-en-un par matière (concaténation des chapitres de cours par transclusion, façon `main.tex` / `sciences.tex`) : [[Cours complet]]

---

## À propos de ce vault

- **Périmètre** : uniquement le cours (Mathématiques + Sciences). Les évaluations, corrections et brouillons du support LaTeX d'origine (`main.tex`, `sciences.tex`, `Evaluations/evaluation.tex`) sont volontairement laissés de côté, à traiter dans un dossier dédié ultérieurement.
- **Callouts** : chaque environnement du cours (définition, propriété, méthode, exemple, remarque, activité, travail, rituel, document, exercice) est un callout Obsidian coloré, style *duoton* — voir `.obsidian/snippets/callouts-premiere.css`.
- **Images** : stockées dans `/Users/cid/Mon Drive/Cours/Images/`, un dossier partagé entre tous les niveaux, relié à ce vault via le lien symbolique `Images/`.
- **Maths et chimie** : rendues nativement par le plugin *Extended MathJax* (la notation chimique `\ce{}` est supportée nativement par MathJax). Les unités `\SI{valeur}{unité}` (non supportées nativement) sont prises en charge par une macro de compatibilité définie dans `preamble.sty` à la racine du vault.
- **Plugins installés** : Latex Suite (raccourcis de saisie), Advanced Tables (édition des tableaux), Extended MathJax (macros).
- **Doublons résolus** : `main.tex` contenait plusieurs chapitres de sciences commentés (brouillons obsolètes, dupliqués avec `sciences.tex`) — c'est `sciences.tex` qui a fait foi pour tout le contenu sciences.
