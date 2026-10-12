---
type: C4 Component
title: Owner data access
status: stable
groma:
  id: ownerrepository
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java
      symbol: OwnerRepository
  group: Clinic data access
  technology: Spring Data JPA
description: Persists owners and searches them by last name.
---

Spring Data JPA repository for Owner records, used by the owner, pet, and visit workflows.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java) | [mysql-database](../../../../../externals/mysql-database.md) | Read and save owners | Spring Data JPA |
| [src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java) | [postgresql-database](../../../../../externals/postgresql-database.md) | Read and save owners | Spring Data JPA |
