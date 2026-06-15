---
{"dg-publish":true,"permalink":"/sen-fi/radical-list-a-z/","dg-note-properties":{}}
---

> [!info] Comprehensive list of radicals sorted alphabetically.

[[Sen'fi/Radical List (Tagged)\|Sort: By Category]]
[[Sen'fi/Glossary (A-Z)\|Show All Words]]

*WIP*


```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - file.folder.startsWith("Sen'fi/Glossary")
        - file.tags.contains("radical")
    order:
      - file.name
      - keyword
      - kanji
      - symbol
    sort:
      - property: file.name
        direction: ASC
    image: note.feature
    imageFit: contain
    imageAspectRatio: 0.7
    cardSize: 150

```
