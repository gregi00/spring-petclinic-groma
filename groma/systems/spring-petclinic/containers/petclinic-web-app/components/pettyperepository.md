---
type: C4 Component
title: Pet type catalog access
status: stable
groma:
  id: pettyperepository
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java
      symbol: PetTypeRepository
  group: Clinic data access
  technology: Spring Data JPA
description: Lists pet types for pet forms.
---

Spring Data JPA repository that returns pet types ordered by name for pet creation and update forms.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java) | [mysql-database](../../../../../externals/mysql-database.md) | Read pet type catalog | Spring Data JPA |
| [src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java) | [postgresql-database](../../../../../externals/postgresql-database.md) | Read pet type catalog | Spring Data JPA |
