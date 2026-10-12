---
type: C4 Component
title: Clinic record model
status: stable
groma:
  id: clinic-records
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/Owner.java
      symbol: Owner
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/Pet.java
      symbol: Pet
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/Visit.java
      symbol: Visit
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/PetType.java
      symbol: PetType
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/vet/Specialty.java
      symbol: Specialty
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/vet/Vet.java
      symbol: Vet
  group: Clinic domain model
  technology: Jakarta Persistence
description: 'Defines the JPA-backed clinic domain: owners, pets, visits, veterinarians, and reference data.'
---

JPA entities represent owners and their pets and visits, plus veterinarians, pet types, and specialties. Owners contain pets, pets contain visits and refer to a pet type, and veterinarians are associated with specialties.
