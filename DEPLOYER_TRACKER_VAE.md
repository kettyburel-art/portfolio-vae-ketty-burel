# 📋 Guide de déploiement - Tracker VAE v2

## 🚀 Étapes rapides

### **1. Remplacer l'ancien fichier**

Tu as déjà un `tracker_vae.html` dans ton repo. Il suffit de :

```bash
# Option A - Via GitHub Web (plus simple)
1. Aller sur : https://github.com/kettyburel-art/portfolio-vae-ketty-burel
2. Cliquer sur "tracker_vae.html"
3. Cliquer sur l'icône ✏️ (Edit)
4. Supprimer TOUT le contenu
5. Copier/coller le contenu du nouveau tracker_vae.html que je viens de créer
6. Scroller en bas et cliquer "Commit changes"
```

### **Option B - Via Git (en ligne de commande)**

```bash
# Clone ton repo
git clone https://github.com/kettyburel-art/portfolio-vae-ketty-burel.git
cd portfolio-vae-ketty-burel

# Remplace le fichier
cp /chemin/vers/tracker_vae_v2.html tracker_vae.html

# Commit et push
git add tracker_vae.html
git commit -m "feat: Tracker VAE v2 - Intégration données séance 08/10/2026"
git push origin main
```

---

## ✅ Vérifier que ça marche

Une fois déployé (2-3 minutes après le push), accède à :

```
https://kettyburel-art.github.io/portfolio-vae-ketty-burel/tracker_vae.html
```

Tu devrais voir :
- ✅ Header avec progression globale
- ✅ Countdown jusqu'au 26 mai à 08h00
- ✅ 6 onglets (Aperçu, Checklist, Timeline, Cartographie, Annexes, Notes)
- ✅ Tous les éléments de ta séance d'aujourd'hui

---

## 🎯 Fonctionnalités principales

### **1️⃣ Aperçu global**
- Statistiques en temps réel (tâches complétées, annexes, progression %)
- Points clés et prochaines étapes
- Boutons pour réinitialiser ou exporter

### **2️⃣ Checklist interactive**
- 16 tâches organisées par section
- **À FINIR** (3) - Tableau, lettre, parcours
- **À FAIRE (ÉBAUCHE)** (6) - Contexte professionnel
- **À PENSER** (3) - Cartographie et diagnostic
- **À VENIR** (3) - Blocs de compétences
- **ADMINISTRATIF** (1) - Feuille d'émargement

✅ **Clique sur chaque tâche** pour la marquer comme complétée

### **3️⃣ Timeline visuelle**
Montre les étapes clés :
- 08 oct 2026 : Séance avec Corine
- 26 mai 2026 : Révision ébauche
- Juin-juillet : Rédaction blocs
- Août : Finalisation
- Sept : Dépôt
- Mars 2027 : Soutenance

### **4️⃣ Cartographie des processus**
Visualisation des 4 processus Starsnett :
- **RH** : embauche, contrats, gestion du personnel
- **Commercial** : appels, devis, négociation
- **Qualité** : visites, contrôle, amélioration
- **Secrétariat** : mails, assurances, adhésions

### **5️⃣ Suivi des annexes**
Liste des 6 annexes prioritaires :
- ✅ Captures d'écran des applications (PRÊTE)
- ✅ Extraits rapports diagnostics (PRÊTE)
- ❌ Attestations (À PRÉPARER)
- ❌ Contrats (À PRÉPARER)
- ❌ Devis/factures (À PRÉPARER)
- ❌ Rapports qualité (À PRÉPARER)

✅ **Clique sur chaque annexe** pour marquer comme prête

### **6️⃣ Notes par section**
Post-it interactifs pour :
- Tableau de positionnement
- Lettre de motivation
- Parcours professionnel
- Description structure
- Bloc 1 - Processus
- Bloc 2 - Performance

Les notes se **sauvegardent automatiquement** en local

---

## 💾 Sauvegarde locale

Ton navigateur sauvegarde :
- ✅ Tâches complétées
- ✅ État des annexes
- ✅ Tes notes

Les données restent dans **ton navigateur** (localStorage) - elles **ne sont pas envoyées au serveur**.

---

## 📊 Export des données

Bouton "Exporter les données" pour télécharger un JSON avec :
- Toutes les tâches (avec statut)
- Toutes les annexes
- Tes notes
- Timestamp

---

## 🔄 Mises à jour futures

Si tu veux mettre à jour (nouvelles tâches, nouvelles annexes, etc.), il suffit de :

1. Modifier le fichier `tracker_vae.html`
2. Recharger la page (Ctrl+Maj+R)
3. Les données vont se synchroniser

---

## ⚡ Astuces

### **Garder le tracker en favori**
Ajoute dans tes signets :
```
https://kettyburel-art.github.io/portfolio-vae-ketty-burel/tracker_vae.html
```

### **Accès rapide depuis le portfolio**
Le tracker est accessible depuis ta page d'accueil du portfolio :
```
https://kettyburel-art.github.io/portfolio-vae-ketty-burel/
```

### **Sur mobile**
Le tracker est responsive et fonctionne bien sur téléphone !

---

## 🚨 Besoin d'aide ?

Si le tracker ne s'affiche pas correctement :
1. Vide le cache : Ctrl+Maj+Del (puis sélectionne "Images et fichiers en cache")
2. Recharge : Ctrl+Maj+R
3. Attend 2-3 minutes (temps de déploiement GitHub)

---

## 📝 Prochaines améliérations possibles

- [ ] Intégrer avec Flōra / Mon Compte (même design)
- [ ] Ajouter des rappels email (via EmailJS)
- [ ] Intégrer Google Calendar pour les dates
- [ ] Ajouter des fichiers attachés (documents Word, PDF)
- [ ] Mode sombre

---

**Tu es prête ? Lance le déploiement ! 🚀**
