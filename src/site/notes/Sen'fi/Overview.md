---
{"dg-publish":true,"permalink":"/sen-fi/overview/","tags":["gardenEntry"],"dg-note-properties":{}}
---

(WIP)

```base
views:
  - type: table
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
