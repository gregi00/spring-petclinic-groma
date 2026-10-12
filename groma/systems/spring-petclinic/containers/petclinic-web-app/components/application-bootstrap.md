---
type: C4 Component
title: Application bootstrap and runtime hints
status: stable
groma:
  id: application-bootstrap
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java
      symbol: PetClinicApplication
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/PetClinicRuntimeHints.java
      symbol: PetClinicRuntimeHints
  technology: Java, Spring Boot AOT
description: Starts Spring Boot and registers runtime hints.
---

The application entry point launches Spring Boot and imports runtime hints that retain database scripts, message bundles, and model types needed by the configured runtime.
