---
authors: # liste des auteurs de l'article
- dremixam
- nelson
checked: true # permet de desactiver le disclaimer en haut de l'article
cover: /content/image/2025/image.jpg # illustration principale
date: '2025-04-14 00:00:00' #date au format aaaa-mm-jj
layout: article # pas touche
tags: # la ou les villes concernés par l'article
- liberty-city
- vice-city
- los-santos
- san-fierro
- las-venturas
title: Titre de l'article # Le titre tel qu'il sera affiché
---

# Introduction au Markdown

Markdown est un langage de balisage léger qui permet de formater du texte de manière simple et lisible. Voici un aperçu des principales fonctionnalités du Markdown.

Vous pourrez rédiger vos articles en Markdown afin que le site puisse automatiquement faire la mise en plage.

Une fois l'article terminé, il doit être ajouté à _posts pour être publié.

---

## 1. Titres
Les titres sont créés en utilisant des dièses (`#`). Plus il y a de dièses, plus le niveau du titre est bas (jusqu'à un maximum de 6).

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3

---

## 2. Gras et italique
- **Gras** : Utilisez deux astérisques (`**`) ou deux tirets bas (`__`).
- *Italique* : Utilisez un astérisque (`*`) ou un tiret bas (`_`).
- ***Gras et italique*** : Combinez trois astérisques (`***`) ou trois tirets bas (`___`).

---

## 3. Listes
### Listes à puces
Utilisez des tirets (`-`), des astérisques (`*`), ou des plus (`+`).

- Élément 1
- Élément 2
  - Sous-élément 2.1
  - Sous-élément 2.2

### Listes numérotées
Utilisez des chiffres suivis d'un point (`1.`).

1. Élément 1
2. Élément 2
   1. Sous-élément 2.1
   2. Sous-élément 2.2

---

## 4. Liens
Créez des liens en utilisant la syntaxe `[texte](URL)`.

[Visitez Google](https://www.google.com)

---

## 5. Images
Ajoutez des images avec la syntaxe `![texte alternatif](URL)` le texte alternatif est utilisé pour l'accessibilité en particulier pour les malvoyants.

![Logo Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

De manière générale, pour une meilleure mise en plage, placez toujours les images seules sur leur ligne. Si vous voulez faire suivre plusieurs images, utilisez un simple retour à la ligne entre chaque image.

![Logo Markdown 1](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
![Logo Markdown 2](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
![Logo Markdown 3](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

Si vous faites suivre un texte en italique (avec _italique_) sur la ligne immédiattement après une image seule, ce texte sera utilisé comme légende pour l'image (Cette fonction est spécifique au Liberty-Tree).

![Logo Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
_Le logo du langage Markdown_

---

## 6. Paragraphes

Pour créer un paragraphe, utilisez simplement deux retours à la ligne successifs entre deux ensembles de texte.

Ceci est un autre paragraphe.

---

## 7. Citations
Utilisez le symbole `>` pour créer des citations.

> Ceci est une citation.
>> Ceci est une citation imbriquée.

---

## 8. Tableaux
Créez des tableaux en utilisant des barres verticales (`|`) et des tirets (`-`).

| Colonne 1 | Colonne 2 | Colonne 3 |
|-----------|-----------|-----------|
| Valeur 1  | Valeur 2  | Valeur 3  |
| Valeur 4  | Valeur 5  | Valeur 6  |

---

## 9. Lignes horizontales
Utilisez trois tirets (`---`), astérisques (`***`), ou underscores (`___`) pour insérer une ligne horizontale de séparation (à éviter dans les articles sauf si ça se justifie vraiment).

---

## 10. Échappement de caractères
Pour afficher des caractères spéciaux (comme `*`, `_`, ou `#`), utilisez une barre oblique inversée (`\`).

\*Texte non formaté\*

---

Markdown est un langage simple mais puissant pour formater du texte. Essayez ces fonctionnalités dans vos propres documents pour voir comment elles fonctionnent !