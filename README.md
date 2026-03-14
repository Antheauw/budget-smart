# 💰 BudgetSmart — Gestionnaire de dépenses fixes

Un outil web **100% statique** pour analyser tes abonnements mensuels, découvrir des alternatives moins chères sur le marché, et construire ton plan d'économies personnalisé.

![HTML](https://img.shields.io/badge/HTML-single%20file-orange) ![CSS](https://img.shields.io/badge/CSS-vanilla-blue) ![JS](https://img.shields.io/badge/JS-vanilla-yellow) ![No backend](https://img.shields.io/badge/backend-aucun-green) ![No tracking](https://img.shields.io/badge/tracking-aucun-green)

---

## ✨ Fonctionnalités

- **Saisie de dépenses** par catégorie : télécom, streaming, banque, énergie, sport, Amazon…
- **Alternatives de marché en temps réel** affichées instantanément sous chaque poste dès qu'un montant est saisi
- **11 pays supportés** : 🇫🇷 🇧🇪 🇨🇭 🇩🇪 🇪🇸 🇮🇹 🇬🇧 🇵🇹 🇺🇸 🇨🇦 🇲🇦
- **Gestion du foyer** : de 1 à 6 personnes, avec calcul correct selon le type d'abonnement :
  - *Par personne* (forfait mobile, salle de sport, banque, Spotify) → prix × nombre de personnes
  - *Partagé foyer* (box internet, Netflix, électricité, Amazon) → prix unique
- **Offres famille** débloquées automatiquement selon le nombre de personnes
- **Plan d'économies** : ajoute les offres qui t'intéressent une par une et visualise combien tu économises par mois, par personne, et par an
- **Drag-to-scroll** sur les listes d'alternatives pour naviguer facilement entre les offres
- **Mode sombre / clair** avec persistance dans le navigateur
- **Liens directs** vers les sites des opérateurs sur chaque offre

---

## 🚀 Utilisation

Aucune installation requise. C'est un fichier HTML unique et autonome.

### Option 1 — En local
```bash
git clone https://github.com/ton-username/budgetsmart.git
# Ouvre simplement depenses-mensuelles.html dans ton navigateur
```

### Option 2 — En ligne
Le site est hébergé sur : **https://antheauw.github.io/budget-smart/**

---

## 🗂️ Structure

```
budgetsmart/
└── depenses-mensuelles.html   # L'application complète (HTML + CSS + JS)
└── README.md
```

Tout est dans un seul fichier. Pas de dépendances npm, pas de build, pas de serveur.

---

## 🌍 Pays & catégories supportés

| Catégorie | Type | Pays |
|---|---|---|
| 📱 Forfait mobile | Par personne | FR BE CH DE ES IT UK PT US CA MA |
| 🌐 Box Internet | Partagé foyer | FR BE CH DE ES IT UK PT US CA MA |
| 📺 Netflix / VOD | Partagé foyer | FR BE CH DE ES IT UK PT US CA MA |
| 🎵 Spotify / Musique | Par personne | FR BE CH DE ES IT UK PT US CA MA |
| 💳 Frais bancaires | Par personne | FR BE CH DE ES IT UK PT US CA MA |
| ⚡ Électricité | Partagé foyer | FR BE CH DE ES IT UK PT US CA MA |
| 🏋️ Salle de sport | Par personne | FR BE CH DE ES IT UK PT US CA MA |
| 📦 Amazon Prime | Partagé foyer | FR BE CH DE ES IT UK PT US CA MA |

---

## ⚠️ Disclaimer

Les prix affichés dans l'application sont **indicatifs** et basés sur les données disponibles au moment de la dernière mise à jour (mars 2026). Les offres des opérateurs changent régulièrement — toujours vérifier le prix exact directement sur le site de l'opérateur avant de prendre une décision.

---

## 🔒 Confidentialité

- **Aucune donnée n'est collectée** ni envoyée sur un serveur
- Tout reste dans ton navigateur
- Le seul stockage utilisé est `localStorage` pour mémoriser le thème (clair/sombre)
- Aucun cookie, aucun tracker, aucune analytics

---

## 🛠️ Contribuer

Les prix et offres évoluent vite ! Si tu constates une erreur ou veux ajouter un opérateur/pays :

1. Fork le repo
2. Modifie la base `MKT` dans le fichier HTML (section bien commentée)
3. Ouvre une Pull Request

---

## 📄 Licence

MIT — libre d'utilisation, de modification et de redistribution.
