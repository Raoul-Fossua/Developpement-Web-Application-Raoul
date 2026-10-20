# Application To Do List — Étapes 1A à 1E

**Auteur** : Raoul FOSSUA TINDO  
**Contexte** : Cours Développement Web et Applications - Unistra  
**Étape** : N1 — Structure des données JSON

---

## 🌐 Application en ligne

👉 **Accéder à l'application sur Alwaysdata**

URL : [https://lovensky.alwaysdata.net/step1E.html](https://lovensky.alwaysdata.net/step1E.html)

---

## 📋 Présentation

Ce projet correspond aux étapes **1A à 1E** du cours de Développement Web et Applications. Il contient les **structures de données JSON** utilisées pour représenter les tâches et leurs critères associés, manipulées en JavaScript avec l'API **LocalStorage**.

---

## 🗂️ Organisation des dossiers

| Dossier | Fichier | Rôle |
|---|---|---|
| `/Etape1/step1A/` | `step1A.json` | Structure d'une tâche (dates + planification + achèvement) |
| `/Etape1/step1B/` | `step1B.json` | Priorités (7 valeurs dégressives) |
| `/Etape1/step1C/` | `step1Ca.json` | Statuts (9 valeurs) |
| `/Etape1/step1C/` | `step1Cb.json` | Niveaux d'accomplissement (5 valeurs) |
| `/Etape1/step1D/` | `step1D.json` | Catégories (5 valeurs) |
| `/Etape1/step1E/` | `step1E.html` | Page HTML + tests + LocalStorage |
| `/Etape2/step2A/` | `step2A.html` / `step2A.css` | Formulaire de saisie (HTML/CSS uniquement) |

---

## 🔗 Relation PK / FK

| Table | Clé primaire | Clés étrangères |
|---|---|---|
| `tasksList` (1A) | `idTask` | `idPriority` → prioritiesList<br>`idStatus` → statusList<br>`idAccomplissement` → accomplissementList<br>`idCategory` → categoriesList |
| `prioritiesList` (1B) | `idPriority` | — |
| `statusList` (1Ca) | `idStatus` | — |
| `accomplissementList` (1Cb) | `idAccomplissement` | — |
| `categoriesList` (1D) | `idCategory` | — |

---

## 🛠️ Manipulations réalisées

Dans `step1E.html` :

- ✅ Création et manipulation de **tableaux** et d'**objets JavaScript**
- ✅ Affichage avec `console.log()`
- ✅ Conversion avec `JSON.stringify()`
- ✅ Reconversion avec `JSON.parse()`
- ✅ Recherche avec `.find()`
- ✅ Parcours avec `.forEach()`
- ✅ Enregistrement avec `localStorage.setItem()`
- ✅ Récupération avec `localStorage.getItem()`

---

## 🚀 Utilisation

1. Ouvrir `step1E/step1E.html` dans un navigateur
2. Appuyer sur **F12** pour ouvrir la console
3. Observer : les 5 tâches, 7 priorités, 9 statuts, 5 accomplissements, 5 catégories, la relation PK/FK et la sérialisation LocalStorage

---

## ✅ Conformité aux consignes  

- ✅ **1A** contient **dates + planification + achèvement souhaité**
- ✅ **1B** contient **uniquement les priorités**
- ✅ **1C** ne contient **pas d'échéances**
- ✅ **1D** ne contient **pas de dates**
- ✅ **1E** écrit **manuellement**
- ✅ **Nomenclature** `step1X.json` (pour script automatique)

---

## 📌 Notes

- Application **Front-End uniquement** (pas de back-end, pas de MySQL)
- Données stockées côté navigateur via **l'API LocalStorage**
- Code **commenté** et **structuré** pour faciliter la maintenance
- Conventions de nommage respectées (`idXxx`, `validXxx`)

---

**© 2026 — Raoul FOSSUA TINDO**