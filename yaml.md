---
title: Yaml
layout: default
---

    Multiline: |
      hello
      world

    Inheritance: &defaults
      a: 2
      b: 3
    
    Inherit:
      <<: *defaults
      b: 4
