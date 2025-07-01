# ✅ Checklist OSINT - Profiling d'identité numérique

Cette checklist aide à structurer mon enquête OSINT complète sur une personne ou une entité, à partir d'un nom, pseudo, photo ou adresse e-mail.

---

## 🔐 1. Préparation

- [ ] Définir la **demande du client** (ce qu’il veut et ce qu’il ne veut PAS)
- [ ] Rappeler les **limites légales** (pas de piratage, pas d'usurpation, info publique uniquement)
- [ ] Identifier les **éléments de départ** :
  - Nom / prénom
  - Pseudo
  - E-mail
  - Photo
  - Localisation estimée
  - Réseaux sociaux connus

---

## 🔎 2. Recherches de base (Open Source)

### 🧍‍♂️ Identité personnelle
- [ ] Rechercher dans Google / Bing (prénom + nom + ville)
- [ ] Tester des Google Dorks
- [ ] Rechercher les profils LinkedIn / Viadeo / Facebook
- [ ] Vérifier mentions dans annuaires, forums, associations

### 🧑‍💻 Pseudos / usernames
- [ ] Utiliser Namechk / whatsmyname.app / Sherlock
- [ ] Vérifier s’il y a un motif d’usage répété de pseudo
- [ ] Voir si le pseudo est relié à des leaks ou anciens comptes

### 📧 E-mails
- [ ] Vérifier via HaveIBeenPwned / DeHashed / IntelligenceX
- [ ] Tester si e-mail est lié à des réseaux sociaux (gravatar, GitHub, Skype)
- [ ] Tester services de validation d’email

### 🖼️ Photos
- [ ] Recherche inversée (Google, Yandex, TinEye, Pimeyes)
- [ ] Analyse EXIF si possible
- [ ] Vérifier présence sur comptes alternatifs

---

## 🌐 3. Réseaux sociaux et forums

- [ ] Rechercher sur :
  - Facebook
  - Instagram
  - Twitter / X
  - TikTok
  - YouTube
  - Discord / Reddit
- [ ] Collecter :
  - Nom d’utilisateur
  - Infos publiques
  - Abonnés / abonnements
  - Groupes rejoints
  - Lieux tagués

---

## 🧭 4. Localisation & contexte

- [ ] Identifier potentielle **ville de résidence**
- [ ] Utiliser Google Maps / Street View / Géoportail pour croiser indices
- [ ] Vérifier infos de l’environnement dans les photos
- [ ] Analyser le comportement en ligne lié à des lieux (ex : check-ins, stories)

---

## 💾 5. Données supplémentaires

- [ ] Vérifier si des données apparaissent dans des **leaks publics**
- [ ] Vérifier s’il existe un **nom de domaine** ou site perso
- [ ] Tester présence dans bases de données accessibles (Whois, SIRENE, etc.)
- [ ] Rechercher des posts dans anciens forums (archives web)

---

## 🧠 6. Analyse et rédaction du rapport

- [ ] Croiser les infos collectées
- [ ] Identifier incohérences, recoupements, liens faibles
- [ ] Faire une **synthèse structurée**
- [ ] Ajouter **sources + captures (si légales)**
- [ ] Intégrer une **mise en garde éthique et juridique** dans le rapport

---

## 🗂️ 7. Archiver / Livrer

- [ ] Organiser les fichiers :
  - `sources.txt`
  - `captures/`
  - `rapport.md` ou `.pdf`
- [ ] Vérifier anonymisation du rapport si besoin
- [ ] Livrer via lien privé (WeTransfer, Mega, lien Notion...)
- [ ] Supprimer les traces locales (si la mission l’exige)

---

## 🧾 8. Log mission (en privé)

- [ ] Durée estimée
- [ ] Difficulté (1 à 5)
- [ ] Ce qui a bien/mal fonctionné
- [ ] À améliorer pour les futures missions
