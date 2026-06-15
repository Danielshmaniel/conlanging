---
{"dg-publish":true,"permalink":"/sen-fi/radical-list-tagged/","dg-note-properties":{}}
---

> [!info] Comprehensive list of radicals grouped by category.

[[Sen'fi/Radical List (A-Z)\|Sort: Only by A-Z]]
[[Sen'fi/Glossary (Tagged)\|Show All Words]]

*WIP*


```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - file.path.startsWith("Sen'fi/Glossary/")
        - file.tags.contains("radical")
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
