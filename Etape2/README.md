# Étape 2 — Formulaires HTML

**Auteur** : Raoul FOSSUA TINDO  
**Contexte** : Cours Développement Web et Applications - Unistra

---

## 📋 Présentation

Cette étape contient la création du formulaire de saisie d'une tâche pour l'application To-Do List. 
Elle est divisée en deux sous-étapes :

*   **Étape 2A (Statique)** : Un formulaire pur HTML/CSS, sans JavaScript, adapté pour le mobile (Mobile First) avec CSS Grid et Flexbox.
*   **Étape 2B (Dynamique)** : Le même formulaire, mais dont les listes déroulantes (`<select>`) sont générées dynamiquement en JavaScript à partir des données JSON de l'étape 1 (via `forEach` et `insertAdjacentHTML`).

---

## 🌐 Application en ligne

*   **Formulaire Statique (2A)** : [https://raoul-fossua.alwaysdata.net/Etape2/step2A/step2A.html](https://raoul-fossua.alwaysdata.net/Etape2/step2A/step2A.html)
*   **Formulaire Dynamique (2B)** : [https://raoul-fossua.alwaysdata.net/Etape2/step2B/step2B.html](https://raoul-fossua.alwaysdata.net/Etape2/step2B/step2B.html)

---

## 🗂️ Organisation des fichiers

| Dossier | Fichier | Rôle |
|---|---|---|
| `/step2A/` | `step2A.html` | Formulaire statique (HTML) |
| `/step2A/` | `step2A.css` | Feuille de style (CSS Grid/Flexbox) |
| `/step2B/` | `step2B.html` | Formulaire dynamique (HTML + JS) |

---

## ✅ Conformité aux consignes

- ✅ **2A** : HTML5 sémantique, CSS pur, Mobile First, validation W3C.
- ✅ **2B** : Écriture dynamique des `<select>` (JS), pas de framework.