<div align="center"><img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png"></div>

---

# 🚀 Cours Complet : Structurer une page Web en HTML5 (Projet « Techium »)

## 🧭 0. Introduction générale

Bienvenue ! Dans ce projet, vous allez apprendre à **utiliser les balises HTML pour structurer** une page web. Aucune feuille de style ; l’aspect visuel sera minimal (« moche »), c’est normal : l’objectif est la **sémantique** et la **structure**.

> ⚠️ **Important :** la syntaxe compte ! Respectez la casse (minuscules), l’orthographe des balises et la fermeture correcte des éléments.

### 📚 Ressources officielles à consulter

* [HTML 5.2 – Spécification W3C](https://www.w3.org/TR/html52/)
* [MDN Web Docs – HTML](https://developer.mozilla.org/fr/docs/Web/HTML)
* [HTML Reference](https://htmlreference.io/)
* [Can I use…](https://caniuse.com/)
* [HTML Cheat Sheet](https://websitesetup.org/html5-cheat-sheet/)

---

## 🎯 1. Objectifs pédagogiques

À la fin de ce cours, vous serez capable :

1. ✅ D’énoncer les **bonnes pratiques** et guidelines HTML.
2. 🏗️ De créer le **squelette** d’une page HTML5 valide.
3. 🧱 D’utiliser les **balises sémantiques** pour structurer un document.
4. 🧩 De choisir entre `<div>` et `<span>` selon le contexte.
5. 🧠 D’exploiter la valeur sémantique de `<header>`, `<main>`, `<footer>`, `<article>`, `<nav>`, `<section>`, `<aside>`.
6. 🔢 De hiérarchiser correctement les titres `h1` → `h6`.
7. 📝 De créer des **listes** (`ul`, `ol`, `dl`).
8. 🖼️ De différencier les formats d’images **SVG, GIF, PNG, JPG**.
9. 📊 De structurer les données tabulaires avec `<table>`.
10. 🎥 D’intégrer une **vidéo** (`<video>`) et un **audio** (`<audio>`).
11. 🌍 D’**embedder** du contenu externe (`<iframe>`, cartes, etc.).
12. ✅ De valider son code avec le **W3C Validator** et de produire un **README.md** clair.

---

## 📘 2. Plan du cours / Modules

| 🧩 Module | Thème                               | Contenu-clé                                                                           |
| --------- | ----------------------------------- | ------------------------------------------------------------------------------------- |
| 2.1       | **Guidelines HTML & accessibilité** | Indentation, casse, attributs obligatoires, ARIA, commentaires.                       |
| 2.2       | **Squelette HTML5**                 | `<!DOCTYPE html>`, `<html lang="fr">`, `<head>`, `<body>`.                            |
| 2.3       | **Balises sémantiques**             | Rôle et exemples de `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`. |
| 2.4       | **Titres & hiérarchie**             | Importance SEO, accessibilité, structure correcte.                                    |
| 2.5       | **div vs span**                     | Cas d'usage, anti-patterns.                                                           |
| 2.6       | **Listes**                          | `ul`, `ol`, `li`, `dl`, `dt`, `dd`.                                                   |
| 2.7       | **Images & médias**                 | `alt`, formats, `<figure>/<figcaption>`.                                              |
| 2.8       | **Tableaux de données**             | `table`, `thead`, `tbody`, `th`, `tr`, `td`.                                          |
| 2.9       | **Audio & Vidéo**                   | Attributs, accessibilité.                                                             |
| 2.10      | **Embed & iframes**                 | `sandbox`, contenus externes.                                                         |
| 2.11      | **Validation & README**             | W3C, organisation du projet.                                                          |

---

## 📋 3. Exigences du projet « Techium »

* 🏢 **Nom de l’entreprise** : Techium (utilisé dans tous les exemples).
* 📄 **README.md** à la racine : description du projet, arborescence, auteurs, licence.
* ✅ **Validation W3C** sans erreur.
* 🗺️ **Sitemap exemple :**

  ```
  index.html          # Page d'accueil
  about.html          # À propos de Techium
  services.html       # Nos services
  contact.html        # Formulaire de contact
  legal.html          # Mentions légales
  ```
* 🧭 **Wireframes** (maquettes de page) à fournir.

---

## 🧪 4. Exemple : squelette HTML de base

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Techium – Accueil</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Techium</h1>
    <nav>
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="about.html">À propos</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Bienvenue chez Techium</h2>
      <p>Notre mission : ...</p>
    </section>
  </main>

  <footer>
    <small>&copy; 2025 Techium. Tous droits réservés.</small>
  </footer>
</body>
</html>
```

---

## 🛠️ 5. Exercices pratiques

1. 🏗️ Créer `index.html` avec `header`, `nav`, `main`, `footer`
2. 📋 Ajouter une liste de services (ul)
3. 📊 Intégrer un tableau tarifaire (`<table>`)
4. 🖼️ Insérer une image SVG du logo Techium avec `alt`
5. 🎞️ Embeder une vidéo (iframe ou `<video>`)
6. ✅ Valider avec [validator.w3.org](https://validator.w3.org)

---

## ❓ 6. Quiz final

1. Pourquoi respecter la hiérarchie `h1` → `h6` ?
2. Différences entre `<section>` et `<article>` ?
3. Quand utiliser `<aside>` ?
4. Quelle balise pour lier une feuille CSS ?
5. Deux attributs obligatoires de `<img>` ?

---

## 📦 7. Livrables attendus

* 🗂️ Dépôt Git contenant :

  * ✅ README.md complet
  * 📄 Pages HTML valides
  * 📁 Dossier `img/` pour médias
  * 🧭 (optionnel) Wireframes
* 🧪 Code valide W3C
* 🧹 Fichiers bien nommés (pas d'espaces, casse correcte)

---
