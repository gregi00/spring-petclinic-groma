---
type: C4 Component
title: Locale support
status: stable
groma:
  id: webconfiguration
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/system/WebConfiguration.java
      symbol: WebConfiguration
  technology: Spring MVC
description: Resolves and changes the active UI language.
---

Spring MVC stores the locale in the user session, defaults to English, and accepts language changes through the lang URL parameter.
