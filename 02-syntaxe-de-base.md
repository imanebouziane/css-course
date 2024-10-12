## 🖍️ Syntaxe de base du CSS

La syntaxe du CSS est simple et se compose de règles de style que l'on applique à des éléments HTML. Chaque **règle CSS** contient les éléments suivants :

1. **Un sélecteur** 🎯 : Il détermine quels éléments HTML seront affectés.
2. **Une ou plusieurs déclaration(s)** 📋 : Une déclaration contient une **propriété** suivie de sa **valeur**. Une propriété spécifie le style à appliquer à l'élément.

### 🌟 Exemple de syntaxe CSS :

```css
/* Sélecteur */
p {
  /* Propriétés: Valeurs; */
  color: blue;
  font-size: 16px;
}
```

### 🛠️ Décomposition de la syntaxe :

- **Sélecteur (p) :** Cible tous les éléments <p> de la page HTML.
- **Propriétés :** Ce sont les caractéristiques que vous souhaitez modifier. Ici, **color** et **font-size**.
- **Valeurs :** Les valeurs spécifient comment chaque propriété doit être modifiée. Ici, **blue** pour la couleur et **16px** pour la taille du texte.

### 🔑 Structure d'une déclaration CSS :

Chaque déclaration est composée de :
- Une propriété (comme color ou font-size)
- Une valeur associée à cette propriété
- Chaque paire propriété-valeur est séparée par un : et la déclaration se termine par un ;

### ✏️ Exemple

```css
h1 {
  color: red;
  text-align: center;
  font-family: Arial, sans-serif;
}
```

Le texte des balises <h1> sera **rouge**, **centré**, et affiché en **Arial** (ou dans une police de secours).

### 🎨 Propriétés les plus courantes en CSS :

| Propriété         | Description                           | Exemple de valeur       |
|-------------------|---------------------------------------|-------------------------|
| `color`           | Définit la couleur du texte           | `red`, `#ff0000`        |
| `background-color`| Définit la couleur d'arrière-plan     | `blue`, `#0000ff`       |
| `font-size`       | Définit la taille de la police        | `16px`, `1.5em`         |
| `text-align`      | Aligne le texte                       | `left`, `center`        |
| `margin`          | Espace autour de l'élément            | `10px`, `auto`          |
| `padding`         | Espace intérieur d'un élément         | `15px`, `5%`            |
| `border`          | Définit la bordure d'un élément       | `1px solid black`       |
