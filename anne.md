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
