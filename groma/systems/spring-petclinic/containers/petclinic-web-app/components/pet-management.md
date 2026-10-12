---
type: C4 Component
title: Pet management
status: stable
groma:
  id: pet-management
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/PetController.java
      symbol: PetController
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java
      symbol: PetValidator
  group: Clinic workflows
  technology: Spring MVC, Jakarta Validation
description: Creates and updates pets for an owner.
---

Spring MVC handlers load an owner and pet, validate pet forms, and save changes through OwnerRepository. Pet types are supplied by PetTypeRepository and converted from form text by PetTypeFormatter.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/owner/PetController.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetController.java) | [src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java) | Load and save owners | Spring dependency injection |
| [src/main/java/org/springframework/samples/petclinic/owner/PetController.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetController.java) | [src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/PetTypeRepository.java) | Load pet types | Spring dependency injection |
