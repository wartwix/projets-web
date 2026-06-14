# 🧪 Projets Web — HTML / CSS / JavaScript

Petits projets JavaScript réalisés en classe, chacun explorant un concept fondamental du développement web front-end.

## 🌐 Démo en ligne

👉 **[https://wartwix.github.io/projets-web/](https://wartwix.github.io/projets-web/)**

Aucun téléchargement nécessaire — ouvrez le lien et utilisez les projets directement dans votre navigateur.

---

## 📦 Projets inclus

### 🔢 Calculatrice (`calculatrice.html`)

Une calculatrice fonctionnelle avec une interface soignée.

- Opérations de base : addition, soustraction, multiplication, division
- Gestion des erreurs de saisie avec message temporaire
- Mise en page avec **CSS Grid**
- Design sombre avec boutons colorés par catégorie

---

### ✅ Gestionnaire de tâches (`projet_tacheee.html`)

Une application de to-do list moderne avec persistance des données.

- Ajouter, cocher et supprimer des tâches
- Les tâches sont **sauvegardées dans le navigateur** via `localStorage` (elles survivent au rechargement)
- Ajout rapide via la touche **Entrée**
- Interface avec dégradé violet et animations CSS

---

### 📝 Éditeur de fichier (`sadra_exo_fichier.html`)

Un outil pour lire, modifier et télécharger des fichiers texte, directement dans le navigateur.

- Chargement d'un fichier local (`txt`, `html`, `csv`, etc.) via l'API **FileReader**
- Édition du contenu dans une zone de texte
- Téléchargement du fichier modifié (renommé automatiquement avec le préfixe `modifie_`)
- Aucune donnée envoyée sur un serveur — tout se passe **100% côté client**

---

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (Flexbox, Grid, animations)
- JavaScript vanilla (DOM, événements, localStorage, FileReader API)

## 🚀 Utilisation en local

Aucune installation requise. Il suffit d'ouvrir l'un des fichiers `.html` dans votre navigateur :

```bash
git clone https://github.com/wartwix/projets-web.git
cd projets-web
# Ouvrir calculatrice.html, projet_tacheee.html ou sadra_exo_fichier.html dans un navigateur
```

## 📁 Structure du projet

```
projets-web/
├── calculatrice.html       # Calculatrice
├── projet_tacheee.html     # Gestionnaire de tâches
├── sadra_exo_fichier.html  # Éditeur de fichier
└── README.md
```
