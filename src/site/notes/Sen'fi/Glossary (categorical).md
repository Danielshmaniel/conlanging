---
{"dg-publish":true,"permalink":"/sen-fi/glossary-categorical/","tags":["gardenEntry"],"dg-note-properties":{}}
---

[[Sen'fi/Glossary (alphabetical)\|Sort: Only by A-Z]]
(WIP)

```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - file.folder.startsWith("Sen'fi/Glossary")
    groupBy:
      property: tags
      direction: DESC
    order:
      - file.name
      - keyword
    sort:
      - property: file.name
        direction: ASC
    image: note.feature
    imageFit: contain
    imageAspectRatio: 0.7
    cardSize: 150

```
