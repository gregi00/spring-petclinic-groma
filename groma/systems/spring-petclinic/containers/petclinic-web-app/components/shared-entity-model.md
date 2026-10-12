---
type: C4 Component
title: Shared entity foundations
status: stable
groma:
  id: shared-entity-model
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java
      symbol: BaseEntity
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java
      symbol: NamedEntity
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/model/Person.java
      symbol: Person
  group: Clinic domain model
  technology: Jakarta Persistence
description: Provides identifiers and shared name fields for clinic entities.
---

Mapped superclasses provide generated identifiers, names, and person-name fields inherited by the clinic record entities.
