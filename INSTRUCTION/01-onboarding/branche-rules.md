# 🌿 Rules des Branches — Hackathon React CODA

Pour assurer une bonne organisation et éviter les conflits Git, voici les règles obligatoires pour toutes les branches du module.

---

## 1️⃣ Nom des branches

Chaque étudiant doit utiliser cette convention :
prenom-nom/jourX

Exemples :
- `alice-dupont/jour1`
- `kevin-rossi/jour3`

Pour un correctif ou un travail particulier :
prenom-nom/fix-formulaire
prenom-nom/feature-routing

---

## 2️⃣ Branches interdites d’accès (protégées)
main

⛔ Aucun push direct  
⛔ Aucun commit direct  
⛔ Merge uniquement par le formateur

---

## 3️⃣ Mises à jour quotidiennes

Chaque matin :

```bash
git checkout main
git pull
git checkout prenom-nom/jourX
```

## 4️⃣ Conflits Git : règles

Si conflit → résoudre localement → commit → push :
```bash
git add .
git commit -m "fix: resolution conflit"
git push
```

⛔ Aucun fichier laissé en état “conflit”.