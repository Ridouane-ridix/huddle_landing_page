# Huddle Landing Page - Design Responsive

Ceci est l'implémentation front-end d'une page de destination (Landing Page) pour l'entreprise fictive **Huddle**. L'objectif principal de ce projet était de créer un design moderne, visuellement agréable, et entièrement **responsive** pour tous les appareils.

---

## 🌟 Fonctionnalités du Projet

* **Design Responsive :** Mise en page optimisée pour les écrans de bureau, les tablettes (jusqu'à `1024px`), et les téléphones mobiles (jusqu'à `320px`), en utilisant des **Media Queries**.
* **Structure HTML Sémantique :** Utilisation de balises appropriées (`<header>`, `<section>`, `<footer>`) pour une bonne organisation du contenu.
* **Composants Modernes :**
    * **Section Héro** avec image et appel à l'action.
    * **Cartes d'Information (`.card`)** avec mise en page inversée pour un meilleur flux visuel.
    * **Carte Flottante (`.floating-card`)** pour un appel à l'action final.
* **Styling Avancé :** Utilisation de **Flexbox** pour l'alignement (`.main-content`, `.flex`) et des variables CSS (`:root`) pour gérer facilement les couleurs du thème.

---

## 🎨 Technologies Utilisées

| Technologie | Rôle |
| :--- | :--- |
| **HTML5** | Structure de la page web. |
| **CSS3** | Style, mise en page (Flexbox) et design responsive (Media Queries). |
| **Google Fonts** | Utilisation des polices **Poppins** et **Open Sans**. |
| **Font Awesome** (SVG) | Icônes des réseaux sociaux dans le pied de page. |

---

## 🚀 Lancement Local

Pour visualiser le projet dans votre navigateur :

1.  **Cloner ou Télécharger** ce dépôt de code.
2.  Assurez-vous que les dossiers `images/` et les fichiers `index.html` et `style.css` sont dans le même répertoire.
3.  Ouvrez le fichier **`index.html`** dans n'importe quel navigateur web.

*(Pour un développement plus fluide, l'utilisation d'une extension comme **Live Server** sur VS Code est recommandée.)*

---

## 🖼️ Structure CSS Remarquable

* **Centrage global du contenu :** Le `<body>` est centré pour les mises en page mobiles pour faciliter la gestion du responsive.
* **`overflow-x: hidden;` sur `body` :** Cette propriété a été utilisée pour désactiver le défilement horizontal et éviter les barres de défilement indésirables causées par un contenu qui dépasse le bord de l'écran.
* **Positionnement du CTA final :** La carte finale est gérée avec un positionnement **`position: absolute;`** à l'intérieur d'un conteneur Flex pour créer un effet visuel flottant juste avant le pied de page.