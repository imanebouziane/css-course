# 🎨 Introduction au CSS

Le **CSS (Cascading Style Sheets)** est un langage de style utilisé pour décrire la présentation d'une page web. Il permet de styliser des éléments HTML en contrôlant des aspects tels que les couleurs, les polices, les espacements, et la mise en page.

## 📝 Qu'est-ce que le CSS ?

CSS est utilisé pour donner un style aux documents HTML. Grâce à CSS, vous pouvez rendre vos pages web visuellement attrayantes et adaptées à différents appareils (ordinateur, tablette, mobile). Voici quelques exemples de ce que CSS permet de faire :

- 🖍️ Modifier les couleurs
- 🔤 Changer les polices de caractères
- 📏 Contrôler les espacements et marges
- 🖼️ Ajouter des images de fond

## 🔗 Inclusion du CSS dans une page HTML

Il existe plusieurs façons d'ajouter du CSS à une page web :

### 1. **CSS Inline** (dans les balises HTML)  
Appliquer du style directement dans un élément HTML en utilisant l'attribut `style`.

```html
<p style="color: blue; font-size: 20px;">Ceci est un paragraphe bleu avec une taille de texte de 20px.</p>
```

### 2. **CSS Interne** (dans la balise <style> du HTML)
Définir les styles directement dans le fichier HTML dans une section <style>.

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Page Exemple</title>
  <style>
    p {
      color: green;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <p>Ceci est un paragraphe vert avec une taille de texte de 18px.</p>
</body>
</html>
```

### 3. **CSS Externe** (dans un fichier séparé .css)
Créer un fichier séparé pour les styles, comme styles.css, et le lier dans votre fichier HTML avec <link>.

```css
/* styles.css */
p {
  color: red;
  font-size: 22px;
}
```

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Page Exemple</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <p>Ceci est un paragraphe stylisé via un fichier CSS externe.</p>
</body>
</html>
```
