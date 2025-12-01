# 🚀 Git Workflow — Formation CODA x SPARKA  
*Version : 2025 — Référence officielle pour les apprenants*

Ce workflow est **strictement appliqué** pendant toute la formation.  
Il simule les pratiques professionnelles d’une vraie équipe de développement.

---

# 🧩 1. Objectif du workflow

- Collaborer en équipe sur un même projet  
- Éviter les conflits Git  
- Travailler avec des branches propres (feature, bugfix)  
- Ouvrir des Pull Requests (PR)  
- Faire valider son travail par un Tech Lead  
- Garantir un code stable sur `main` et `develop`

---

# 🌿 2. Branches du projet

## 🟩 `main`  
→ Branche stable  
→ Aucun push direct — PR obligatoire  
→ Validée par le formateur

## 🟧 `develop`  
→ Branche de travail des équipes  
→ Le Tech Lead valide les PR feature/bugfix  
→ Base des challenges quotidiens

## 🟦 Branches d’équipe  
- Groupe 1 → `g1/feature/...`  
- Groupe 2 → `g2/bugfix/...`  
- etc.

---

# 🧲 3. Rôles (rotation quotidienne)

### 🧑‍💼 Tech Lead  
- Valide les PR  
- Gère les conflits simples  
- Fusionne vers `develop`  
- Vérifie la qualité du code

### 👩‍💻 Feature Developer  
- Crée `feature/nom-fonctionnalite`  
- Développe une mini-feature du challenge  
- Ouvre une PR → `develop`

### 🧪 Bugfix Developer  
- Crée `bugfix/nom-du-bug`  
- Corrige un bug (fourni dans le challenge)  
- Ouvre une PR → `develop`

---

# 🔁 4. Cycle de travail

1. Chaque étudiant crée une branche (`feature/...` ou `bugfix/...`)  
2. Travaille dessus  
3. Ouvre une Pull Request → `develop`  
4. Le Tech Lead valide  
5. Le formateur fusionne vers `main` si nécessaire  

---

🎯 Résultat : un flux Git propre, professionnel et compréhensible.
