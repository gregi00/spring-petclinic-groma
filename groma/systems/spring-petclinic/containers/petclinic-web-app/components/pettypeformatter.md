---
type: C4 Component
title: Pet type form conversion
status: stable
groma:
  id: pettypeformatter
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java
      symbol: PetTypeFormatter
  group: Clinic workflows
  technology: Spring MVC Formatter
description: Converts pet types between form text and domain objects.
---

The Spring MVC formatter resolves submitted pet type names and prints pet type values using PetTypeRepository.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java) | [src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java) | Resolve pet type names | Spring dependency injection |
