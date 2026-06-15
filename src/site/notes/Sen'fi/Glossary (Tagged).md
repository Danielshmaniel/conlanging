---
{"dg-publish":true,"permalink":"/sen-fi/glossary-tagged/","dg-note-properties":{}}
---

> [!info] Contains all words, including compounds and radicals, grouped by category.

[[Sen'fi/Glossary (A-Z)\|Sort: Only by A-Z]]
[[Sen'fi/Radical List (Tagged)\|Show Only Radicals]]

*WIP*


```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - file.path.startsWith("Sen'fi/Glossary/")
    groupBy:
      property: tags
      direction: ASC
    order:
      - file.name
      - keyword
      - kanji
      - symbol
    sort: []
    image: note.feature
    imageFit: contain
    imageAspectRatio: 0.7
    cardSize: 150

```
