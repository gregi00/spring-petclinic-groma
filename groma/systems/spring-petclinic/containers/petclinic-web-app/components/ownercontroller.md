---
type: C4 Component
title: Owner management
status: stable
groma:
  id: ownercontroller
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java
      symbol: OwnerController
  group: Clinic workflows
  technology: Spring MVC
description: Searches, creates, updates, and displays owners.
---

Spring MVC handlers bind owner forms, search by last name, and save owner records through OwnerRepository before displaying an owner profile.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java) | [src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java) | Search and save owners | Spring dependency injection |
