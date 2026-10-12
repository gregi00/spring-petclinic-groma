---
type: C4 Component
title: Veterinarian cache configuration
status: stable
groma:
  id: cacheconfiguration
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java
      symbol: CacheConfiguration
  technology: Spring Cache, JCache
description: Configures the cache used for veterinarian lookups.
---

Enables Spring caching and creates the statistics-enabled JCache cache named vets, which VetRepository uses for read methods.
