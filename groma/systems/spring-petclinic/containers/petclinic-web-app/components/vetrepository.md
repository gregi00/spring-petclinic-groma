---
type: C4 Component
title: Veterinarian data access
status: stable
groma:
  id: vetrepository
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java
      symbol: VetRepository
  group: Clinic data access
  technology: Spring Data, JCache
description: Reads veterinarians for the directory.
---

Spring Data repository returns all veterinarians, optionally paginated; its read methods use the JCache vets cache.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java) | [mysql-database](../../../../../externals/mysql-database.md) | Read veterinarian directory | Spring Data JPA |
| [src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java) | [postgresql-database](../../../../../externals/postgresql-database.md) | Read veterinarian directory | Spring Data JPA |
