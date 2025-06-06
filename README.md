# Jadoo : un voyage culinaire gourmet

## Description
Le projet **Jadoo** représente un voyage culinaire gourmet et gourmand, accueillant les convives dans une ambiance zen et épurée. Il a pour but de faire découvrir ou redécouvrir la cuisine gastronomique du Chef Junichi IIDA. Le site web offre une expérience immersive, permettant aux utilisateurs de découvrir de nouveaux plats, d'explorer le menu, d'en apprendre davantage sur la philosophie culinaire du chef et de commander facilement leurs repas en ligne.

---

## Fonctionnalités principales
### Sections du site

1.  **Introduction**:
    - Accueille les visiteurs chez Jadoo, en soulignant son voyage culinaire gourmet et gourmand.
    - Met en avant l'ambiance zen et épurée, idéale pour découvrir la cuisine gastronomique du Chef Junichi IIDA.
    - Propose un appel à l'action proéminent "Découvrir la carte".

2.  **Découvrir les Nouveautés et le Menu**:
    - Présente "Les nouveautés Jadoo" avec des images alléchantes et des descriptions des créations culinaires récentes, comme les boulettes de poulet au gingembre ou les nouilles Udon.
    - Affiche une sélection de "Maki" avec des détails tels que "California Tobiko" et "Ebi", accompagnés d'animations décoratives.
    - Inclut un bouton "Découvrir la carte", encourageant une exploration plus approfondie.

3.  **Le Voyage avec la cuisine du chef**:
    - Propose une section vidéo (avec un bouton de lecture) offrant un aperçu du service du chef ou de l'ambiance du restaurant.
    - Met en lumière le voyage gastronomique du Chef Junichi IIDA entre le Japon et la France, soulignant son expérience dans des maisons étoilées.
    - Présente des illustrations liées au chef et à l'art culinaire.

4.  **Commander**:
    - Souligne la rapidité et la praticité de la commande en ligne.
    - Offre la possibilité de commander via UberEats ou directement sur le site officiel de Jadoo.
    - Promet une "Livraison ultra rapide" en 20 minutes maximum.
    - Inclut un autre bouton "Découvrir la carte".

5.  **Contact et Réservations**:
    - Se concentre sur la prise de rendez-vous et la réservation au restaurant.
    - Comprend un formulaire de contact pour les demandes, demandant le nom, le prénom, l'adresse e-mail et le message.
    - Est complétée par une illustration visuelle pour la section contact.

### Éléments interactifs
-   **Navigation :** Un en-tête avec le logo Jadoo, un menu burger pour mobile et des liens de navigation vers les différentes sections du site.
-   **Boutons d'appel à l'action :** Des boutons jaunes proéminents sur l'ensemble du site encouragent les utilisateurs à "Découvrir la carte" ou à "Envoyer" le formulaire de contact.
-   **Effets de survol :** Des animations subtiles sur des éléments tels que les cartes de maki (indiquées par la classe `animation_maki`).

---

## Installation
### Étapes pour lancer le projet localement
1.  **Clonez ce dépôt (ou téléchargez les fichiers) :**
    ```bash
    git clone [https://github.com/Only-tech/jadoo_html_css_]
    ```
2.  **Naviguez jusqu'au répertoire du projet.**
3.  **Ouvrez le fichier `index.html` dans votre navigateur web.**

### Structure des fichiers
```
/
├── index.html (Page principale en français)
├── css/
│   └── style.css (Styles principaux du site web)
│   └── fonts.css (Déclarations des polices)
├── fonts/
│   └── Montserrat (Contient les polices)
│   └── Open_Sans (Contient les polices)
│   └── Oswald (Contient les polices)
│   └── Poppins (Contient les polices)
│   └── Volkhov (Contient les polices)
├── img/ 
│   └── images (Contient les images, logos et illustrations)
├── README
```
---

## Technologies utilisées
### Développement
-   **HTML5** : Structure et contenu des pages web.
-   **CSS3** : Style, mise en page et animations pour un design moderne et attrayant.

### Conception
-   **Figma** : Site réalisé avec pour model le visuel sur figma 

### Autres outils
-   **VS Code** : Éditeur de code principal pour le développement.
-   **GIT et GITHUB**.

### Conception adaptative (Responsive Design)
Le site web Jadoo est conçu pour être entièrement adaptatif, garantissant une expérience de visualisation optimale sur une large gamme d'appareils :
-   **Ordinateurs de bureau** : Visuels riches et mises en page de sections claires.
-   **Tablettes et appareils mobiles** :
    * Une icône "burger" pour le menu de navigation assure un accès facile sur les petits écrans.
    * Les mises en page et les tailles de police s'ajustent automatiquement pour une lisibilité et une convivialité accrues.
    * Les informations de contact sont visibles sur mobile.

---

## Extraits de code
### Exemple d'une section du menu (Maki)

Voici un exemple d'une des sections du menu dans `index.html`, illustrant la présentation des makis avec une légende et une animation décorative :

```html
<article class="carte">
    <figure>
        <img src="img/images/maki_1.png" alt="">
        <figcaption>
            <p>California Tobiko</p>
            <p>Saumon, thon, mayonnaise</p>
        </figcaption>
        <div class="animation_maki">                            
            <img src="img/images/decoration_rose.svg" alt="">
        </div>
    </figure>
</article>
```
---

##Crédits
- **Développeur** : Cedrick F.
- **Conception** : Onlineformapro

---
Licence
---
