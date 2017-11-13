---
    # Builtin values
    references:
        - references.md
        - abbreviations.md
        - footnotes.md

    destination: IMPLEMENTATIONS.html

    # Meta Data
    tags: [Mapbox, tileserver-gl, MBTiles]
    title: Implementation notes
    output:
        - html_document:
            - toc: true
            - toc_depth: 3
    author:
        - Anne

    # Settings overrides
    settings:
        enabled_extensions:
        - extra
        - github
        - toc(title=Table of content, baselevel=4)
        - headerid
        - smarty(smart_quotes=False) # smart quotes interferes with attr_list
        - meta
        - wikilinks
        - admonition
        - codehilite(guess_lang=False,pygments_style=github,linenums=true)
    extra_css:
        - './README.css'
---
<!-- http://www.mkdocs.org/user-guide/configuration/ -->

<h1>Anne</h1>

[TOC]

# Section 
## Sous-section 
Ici du texte ainsi qu'une liste:
- Item 1
- Item 2
    + Tout ça 
    + Tout ça ...

# Une autre section
## Et tout
### voilà

# Un des avantage de ce langage
C'est simple, tout le monde l'utilise et du coup on peut piquer des trucs à gauche à droite:

Palette      | Hex       | RGB           | HSL             | ![Color Picker Boxes](https://draculatheme.com/assets/img/color-boxes/eyedropper.png)
---          | ---       | ---           | ---             | ---
Background   | `#282a36` | `40 42 54`    | `231° 15% 18%`  | ![Background Color](https://draculatheme.com/assets/img/color-boxes/background.png)
Current Line | `#44475a` | `68 71 90`    | `232° 14% 31%`  | ![Current Line Color](https://draculatheme.com/assets/img/color-boxes/current_line.png)
Selection    | `#44475a` | `68 71 90`    | `232° 14% 31%`  | ![Selection Color](https://draculatheme.com/assets/img/color-boxes/selection.png)
Foreground   | `#f8f8f2` | `248 248 242` | `60° 30% 96%`   | ![Foreground Color](https://draculatheme.com/assets/img/color-boxes/foreground.png)
Comment      | `#6272a4` | `98 114 164`  | `225° 27% 51%`  | ![Comment Color](https://draculatheme.com/assets/img/color-boxes/comment.png)
Cyan         | `#8be9fd` | `139 233 253` | `191° 97% 77%`  | ![Cyan Color](https://draculatheme.com/assets/img/color-boxes/cyan.png)
Green        | `#50fa7b` | `80 250 123`  | `135° 94% 65%`  | ![Green Color](https://draculatheme.com/assets/img/color-boxes/green.png)
Orange       | `#ffb86c` | `255 184 108` | `31° 100% 71%`  | ![Orange Color](https://draculatheme.com/assets/img/color-boxes/orange.png)
Pink         | `#ff79c6` | `255 121 198` | `326° 100% 74%` | ![Pink Color](https://draculatheme.com/assets/img/color-boxes/pink.png)
Purple       | `#bd93f9` | `189 147 249` | `265° 89% 78%`  | ![Purple Color](https://draculatheme.com/assets/img/color-boxes/purple.png)
Red          | `#ff5555` | `255 85 85`   | `0° 100% 67%`   | ![Red Color](https://draculatheme.com/assets/img/color-boxes/red.png)
Yellow       | `#f1fa8c` | `241 250 140` | `65° 92% 76%`   | ![Yellow Color](https://draculatheme.com/assets/img/color-boxes/yellow.png)
