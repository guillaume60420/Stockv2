# 📦 C2MI - Gestion Stock Filtres

Application de gestion intelligente des stocks de filtres pour la maintenance SNCF.

## 🎯 Fonctionnalités

- **Gestion du stock** par machine (4'AXE, SKYRAILER, ELAN, etc.)
- **Ajout de pièces** avec scanner de code-barres
- **Retrait intelligent** par kit ou par liste personnalisée
- **Prévisions automatiques** : récupère les engins depuis C2MI et calcule les ruptures de stock

## 🔗 Intégration C2MI

Cette app se connecte au même Firebase que C2MI (`maintenance-c2mi`).

Elle récupère automatiquement la liste des engins pour calculer les prévisions de stock de manière intelligente.

## 🚀 Déploiement

Voir le fichier `DEPLOIEMENT_VERCEL.md` pour les instructions complètes.

**Rapide :**
```bash
npm install -g vercel
vercel
```

## 📱 Utilisation

1. Sélectionne une machine (ex: 4'AXE)
2. Utilise les 4 sections : STOCK / AJOUTER / RETIRER / PRÉVISION
3. Dans PRÉVISION : coche les engins à intervenir → calcul automatique !

## 🔧 Structure

```
stock/
└── index.html    ← App complète (HTML + CSS + JS + Firebase)
```

Tout en un seul fichier pour faciliter le déploiement !

---

**Créé pour SNCF Logistique - C2MI**
